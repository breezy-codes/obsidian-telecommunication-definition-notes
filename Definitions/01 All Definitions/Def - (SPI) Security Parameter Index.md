---
aliases:
  - Security Parameter Index
  - SPI
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Security Parameter Index ([[Def - (SPI) Security Parameter Index|SPI]])** is a **unique 32-bit identifier** used in **[[Def - (IPsec) Internet Protocol Security|IPSec]]** to distinguish between different **Security Associations ([[Def - (SAs) Security Associations|SAs]])**. It appears in the headers of [[Def - (IPsec) Internet Protocol Security|IPSec]] packets, specifically in **[[Def - (ESP) Encapsulating Security Payload|ESP]]** and **[[Def - (AH) Authentication Header|AH]]**, and allows the receiving system to determine which cryptographic parameters to use to process the packet.

Each [[Def - (SAs) Security Associations|SA]] has its own [[Def - (SPI) Security Parameter Index|SPI]], which is:
- **Assigned by the receiver** during [[Def - (IKE) Internet Key Exchange|IKE]] negotiation or manual configuration.
- **Locally unique**: Within the receiving system, no two active [[Def - (SAs) Security Associations|SAs]] should have the same [[Def - (SPI) Security Parameter Index|SPI]].
- **Combined with [[Def - (IP) Internet Protocol|IP]] addresses and protocol ([[Def - (ESP) Encapsulating Security Payload|ESP]]/[[Def - (AH) Authentication Header|AH]])**: Together, they form a tuple that uniquely identifies an [[Def - (SAs) Security Associations|SA]].

[[Def - (SPI) Security Parameter Index|SPI]] is found in:
- **[[Def - (ESP) Encapsulating Security Payload|ESP]] header**: In [[Def - (ESP) Encapsulating Security Payload|ESP]] packets, the [[Def - (SPI) Security Parameter Index|SPI]] appears as the first field, followed by the sequence number and encrypted payload.
- **[[Def - (AH) Authentication Header|AH]] header**: Similarly, [[Def - (AH) Authentication Header|AH]] packets contain the [[Def - (SPI) Security Parameter Index|SPI]] to signal which [[Def - (SAs) Security Associations|SA]] is used for authentication.

By using the [[Def - (SPI) Security Parameter Index|SPI]], [[Def - (IPsec) Internet Protocol Security|IPSec]] devices can efficiently locate the correct decryption keys, algorithms, and integrity checks in the **Security Association Database ([[Def - (SAD) Security Association Database|SAD]])**. This allows high-performance processing of secure traffic without deep inspection of packet content.
