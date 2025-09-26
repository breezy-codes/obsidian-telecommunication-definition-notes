---
aliases:
  - Encapsulating Security Payload
  - ESP
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Encapsulating Security Payload ([[Def - (ESP) Encapsulating Security Payload|ESP]])** is one of the two main security protocols used by **[[Def - (IPsec) Internet Protocol Security|IPSec]]**, designed to provide **confidentiality, data origin authentication, and integrity** for [[Def - (IP) Internet Protocol|IP]] packets. [[Def - (ESP) Encapsulating Security Payload|ESP]] can operate in **transport** or **tunnel** mode and supports encryption as well as optional integrity protection.

[[Def - (ESP) Encapsulating Security Payload|ESP]] encapsulates the payload of the IP packet and can also encrypt portions of the header depending on the mode:
- **Transport mode**: Encrypts only the payload and [[Def - (ESP) Encapsulating Security Payload|ESP]] trailer, leaving the original [[Def - (IP) Internet Protocol|IP]] header intact.
- **Tunnel mode**: Encrypts the entire original IP packet and adds a new outer [[Def - (IP) Internet Protocol|IP]] header, typically used in [[Def - (VPN) Virtual Private Network|VPN]]s between gateways.

[[Def - (ESP) Encapsulating Security Payload|ESP]] structure includes:
- **ESP Header**: Contains the [[Def - (SPI) Security Parameter Index|SPI]] and sequence number.
- **Encrypted Payload**: The data being protected.
- **ESP Trailer**: Includes padding and padding length.
- **Integrity Check Value (optional)**: Verifies the authenticity of the packet if enabled.

Benefits of [[Def - (ESP) Encapsulating Security Payload|ESP]]:
- **Encryption**: Uses symmetric algorithms like AES to prevent data eavesdropping.
- **Authentication**: Ensures packets come from legitimate sources (when integrity is enabled).
- **Widely used**: Preferred over [[Def - (AH) Authentication Header|AH]] for its encryption capabilities.

[[Def - (ESP) Encapsulating Security Payload|ESP]] is more commonly deployed than **AH**, as it supports both confidentiality and authentication, making it suitable for securing internet-facing or private [[Def - (IP) Internet Protocol|IP]] traffic.
