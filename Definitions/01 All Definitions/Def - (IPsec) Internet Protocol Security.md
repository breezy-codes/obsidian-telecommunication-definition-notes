---
aliases:
  - Internet Protocol Security
  - IPSec
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**[[Def - (IPsec) Internet Protocol Security|IPSec]] (Internet Protocol Security)** is a suite of protocols used to **secure [[Def - (IP) Internet Protocol|IP]] communication** by authenticating and encrypting each [[Def - (IP) Internet Protocol|IP]] packet in a data stream. Operating at the **network layer**, [[Def - (IPsec) Internet Protocol Security|IPSec]] provides end-to-end security for applications, without requiring changes to the applications themselves.

[[Def - (IPsec) Internet Protocol Security|IPSec]] can be deployed in two modes:
- **Transport mode**: Encrypts only the payload of [[Def - (IP) Internet Protocol|IP]] packets, leaving the headers intact. Used for host-to-host communication (e.g. between two servers).
- **Tunnel mode**: Encrypts the entire [[Def - (IPv6) Internet Protocol version 6|IPv6]] packet and encapsulates it in a new [[Def - (IP) Internet Protocol|IP]] header. Used in site-to-site [[Def - (VPN) Virtual Private Network|VPN]]s or between gateways.

Core components of [[Def - (IPsec) Internet Protocol Security|IPSec]]:
- **Authentication Header ([[Def - (AH) Authentication Header|AH]])**: Provides data integrity and origin authentication but no encryption.
- **Encapsulating Security Payload ([[Def - (ESP) Encapsulating Security Payload|ESP]])**: Offers encryption, integrity, and authentication for confidentiality and protection against tampering.
- **Security Associations ([[Def - (SAs) Security Associations|SAs]])**: Define parameters for communication between peers, including keys and algorithms.
- **[[Def - (IKE) Internet Key Exchange|IKE]] (Internet Key Exchange)**: A protocol used to negotiate and establish shared keys and SAs between devices.

Benefits of [[Def - (IPsec) Internet Protocol Security|IPSec]]:
- **Transparent to applications**: Secures all [[Def - (IP) Internet Protocol|IP]] traffic without application-level changes.
- **Interoperability**: Works with both [[Def - (IPv4) Internet Protocol version 4|IPv4]] and [[Def - (IPv6) Internet Protocol version 6|IPv6]].
- **Flexibility**: Can protect traffic between hosts, networks, or gateways.

[[Def - (IPsec) Internet Protocol Security|IPSec]] is widely used in **[[Def - (VPN) Virtual Private Network|VPN]]s**, secure remote access, and internal communications between trusted infrastructure components. In [[Def - (IPv6) Internet Protocol version 6|IPv6]], [[Def - (IPsec) Internet Protocol Security|IPSec]] is a mandatory feature, though its use remains optional in practice.
