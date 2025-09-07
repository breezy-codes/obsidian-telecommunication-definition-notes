---
aliases:
  - Security Associations
  - SAs
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---
**Security Associations ([[Def - (SAs) Security Associations|SAs]])** are the **core building blocks of [[Def - (IPsec) Internet Protocol Security|IPSec]]**, defining the parameters used to secure communication between two [[Def - (IPsec) Internet Protocol Security|IPSec]] peers. An [[Def - (SAs) Security Associations|SA]] is a **unidirectional logical connection** that establishes a shared understanding of how to encrypt, authenticate, and manage packets exchanged across a secure channel.

Each [[Def - (SAs) Security Associations|SA]] includes:
- **Security protocol**: [[Def - (ESP) Encapsulating Security Payload|ESP]] or [[Def - (AH) Authentication Header|AH]].
- **Encryption and integrity algorithms**: Such as AES, SHA-2, etc.
- **Keys**: Symmetric keys used for encryption and/or authentication.
- **[[Def - (SPI) Security Parameter Index|SPI]] (Security Parameter Index)**: A unique identifier used to distinguish one [[Def - (SAs) Security Associations|SA]] from another.
- **Lifetime and expiry**: Time or byte limits after which the [[Def - (SAs) Security Associations|SA]] must be renegotiated.

In [[Def - (IPsec) Internet Protocol Security|IPSec]]:
- **Two [[Def - (SAs) Security Associations|SAs]] are required for bidirectional communication**: One for each direction.
- **Transport and tunnel modes** use [[Def - (SAs) Security Associations|SAs]] to define how packet headers and payloads are protected.
- [[Def - (SAs) Security Associations|SAs]] are negotiated and maintained via **Internet Key Exchange ([[Def - (IKE) Internet Key Exchange|IKE]])** protocols, which automate key management.

[[Def - (SAs) Security Associations|SAs]] are stored in the **Security Association Database ([[Def - (SAD) Security Association Database|SAD]])** and referenced when processing [[Def - (IPsec) Internet Protocol Security|IPSec]] traffic. They ensure consistent, secure handling of packets and form the trust backbone between communicating hosts or gateways.
