---
aliases:
  - Security Policy Database
  - SPD
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Security Policy Database ([[Def - (SPD) Security Policy Database|SPD]])** is a **central rule set** used in [[Def - (IPsec) Internet Protocol Security|IPSec]] to determine **how network traffic should be treated with respect to security**. It defines the **security policies** that govern whether packets should be **protected (via [[Def - (IPsec) Internet Protocol Security|IPSec]])**, **bypassed**, or **discarded**.

The [[Def - (SPD) Security Policy Database|SPD]] is consulted **before any [[Def - (IPsec) Internet Protocol Security|IPSec]] processing occurs**, both when sending and receiving packets. It acts as a filtering and decision engine that maps traffic flows to Security Associations ([[Def - (SAs) Security Associations|SAs]]), enabling or enforcing protection according to predefined criteria.

Each [[Def - (SPD) Security Policy Database|SPD]] entry typically specifies:
- **Selectors**: Match criteria such as source/destination [[Def - (IP) Internet Protocol|IP]] addresses, protocol (e.g. [[Def - (TCP) Transmission Control Protocol|TCP]], [[Def - (UDP) User Datagram Protocol|UDP]]), and port numbers.
- **Action**: One of the following:
  - **PROTECT**: Apply [[Def - (IPsec) Internet Protocol Security|IPSec]] (e.g. [[Def - (ESP) Encapsulating Security Payload|ESP]] or[[Def - (AH) Authentication Header|AH]]) using a specific [[Def - (SAs) Security Associations|SAs]].
  - **BYPASS**: Allow the packet without applying [[Def - (IPsec) Internet Protocol Security|IPSec]].
  - **DISCARD**: Drop the packet entirely.
- **Direction**: Whether the policy applies to inbound or outbound traffic.

Key characteristics:
- **Tied to the [[Def - (SAD) Security Association Database|SAD]]**: When a policy requires protection, it references an entry in the Security Association Database ([[Def - (SAD) Security Association Database|SAD]]), which contains the cryptographic details.
- **Supports policy-based and tunnel-based [[Def - (VPN) Virtual Private Network|VPN]]s**: Enables selective or broad protection depending on deployment goals.
- **Defined manually or via [[Def - (IKE) Internet Key Exchange|IKE]]**: In static configurations, administrators define [[Def - (SPD) Security Policy Database|SPD]] entries; in dynamic setups, policies may be derived from [[Def - (IKE) Internet Key Exchange|IKE]] negotiation.

In summary, the [[Def - (SPD) Security Policy Database|SPD]] ensures that only traffic meeting specified security policies is subject to [[Def - (IPsec) Internet Protocol Security|IPSec]] processing, enforcing **granular control** over what is protected, what is excluded, and how traffic flows are secured.