---
aliases:
  - Internet Key Exchange
  - IKE
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
  - telecommunications/OSI-model/layer4
---

**Internet Key Exchange ([[Def - (IKE) Internet Key Exchange|IKE]])** is a protocol used to **establish and manage Security Associations ([[Def - (SAs) Security Associations|SAs]])** in [[Def - (IPsec) Internet Protocol Security|IPSec]]. It automates the negotiation of cryptographic algorithms, authentication methods, and key generation, eliminating the need for manual key configuration between [[Def - (IPsec) Internet Protocol Security|IPSec]] peers.

IKE operates in two main phases:
- **Phase 1**: Establishes an **IKE SA** using either Main Mode or Aggressive Mode. This SA secures further negotiation messages.
- **Phase 2**: Establishes one or more **IPsec SAs** using Quick Mode, defining parameters for [[Def - (ESP) Encapsulating Security Payload|ESP]] or [[Def - (AH) Authentication Header|AH]].

IKE features:
- **Mutual authentication**: Using pre-shared keys, digital certificates ([[Def - (PKI) Public Key Infrastructure|PKI]]), or EAP.
- **Key exchange**: Based on the **Diffie–Hellman** algorithm to derive shared secrets.
- **Replay protection and anti-DOS**: Sequence numbers and cookies help prevent spoofing and flooding.

Versions:
- **IKEv1**: The original version, now largely replaced.
- **IKEv2**: A streamlined, more secure, and reliable version, defined in RFC 7296. It supports [[Def - (NAT) Network Address Translation|NAT]] traversal, MOBIKE (for mobility), and better resilience to failures.

[[Def - (IKE) Internet Key Exchange|IKE]] simplifies and strengthens IPsec deployments by handling all aspects of secure SA establishment and lifecycle management.
