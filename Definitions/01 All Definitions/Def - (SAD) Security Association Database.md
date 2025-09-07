---
aliases:
  - Security Association Database
  - SAD
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Security Association Database ([[Def - (SAD) Security Association Database|SAD]])** is a **local data structure** maintained by an [[Def - (IPsec) Internet Protocol Security|IPSec]]-enabled device that stores all **active Security Associations ([[Def - (SAs) Security Associations|SAs]])**. Each entry in the [[Def - (SAD) Security Association Database|SAD]] contains the cryptographic and transport parameters necessary to process [[Def - (IPsec) Internet Protocol Security|IPSec]] packets associated with a given [[Def - (SPI) Security Parameter Index|SPI]].

Each [[Def - (SAD) Security Association Database|SAD]] entry includes:
- **[[Def - (SPI) Security Parameter Index|SPI]] (Security Parameter Index)**: Used to match incoming packets with the correct [[Def - (SAs) Security Associations|SA]].
- **Destination and source IP addresses**
- **Security protocol**: [[Def - (ESP) Encapsulating Security Payload|ESP]] or [[Def - (AH) Authentication Header|AH]].
- **Encryption and integrity algorithms**: e.g. AES, SHA-2.
- **Keys**: Symmetric keys used for encryption and/or authentication.
- **Sequence numbers and anti-replay windows**
- **Lifetime**: Time-based or volume-based expiration settings.

The [[Def - (SAD) Security Association Database|SAD]] is used for:
- **Inbound processing**: When a secured packet arrives, the device looks up the [[Def - (SPI) Security Parameter Index|SPI]] in the [[Def - (SAD) Security Association Database|SAD]] to decrypt or verify the packet.
- **Outbound processing**: The device references the [[Def - (SAD) Security Association Database|SAD]] to construct [[Def - (IPsec) Internet Protocol Security|IPSec]] headers and apply the appropriate cryptographic transformations before sending.

The [[Def - (SAD) Security Association Database|SAD]] is typically managed alongside the **Security Policy Database ([[Def - (SPD) Security Policy Database|SPD]])**, which defines the rules for when and how [[Def - (IPsec) Internet Protocol Security|IPSec]] should be applied. While the [[Def - (SPD) Security Policy Database|SPD]] determines *what to protect*, the [[Def - (SAD) Security Association Database|SAD]] provides the *details for how to protect it*.
