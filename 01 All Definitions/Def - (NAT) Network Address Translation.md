---
aliases:
  - Network Address Translation
  - NAT
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Network Address Translation ([[Def - (NAT) Network Address Translation|NAT]])** is a technique used in [[Def - (IPv4) Internet Protocol version 4|IPv4]] networks to modify [[Def - (IP) Internet Protocol|IP]] address information in packet headers as they traverse a router or firewall. It allows multiple devices on a private network to share a single public [[Def - (IP) Internet Protocol|IP]] address when accessing external networks like the internet.

[[Def - (NAT) Network Address Translation|NAT]] was developed as a workaround for **[[Def - (IPv4) Internet Protocol version 4|IPv4]] address exhaustion**. It maps private [[Def - (IP) Internet Protocol|IP]] addresses (from ranges defined in RFC 1918) to one or more public addresses at the network edge.

Common types of [[Def - (NAT) Network Address Translation|NAT]]:
- **Static [[Def - (NAT) Network Address Translation|NAT]]**: One-to-one mapping between a private and a public [[Def - (IP) Internet Protocol|IP]].
- **Dynamic [[Def - (NAT) Network Address Translation|NAT]]**: Maps private addresses to a pool of public addresses.
- **[[Def - (PAT) Port Address Translation|PAT]] (Port Address Translation)**: Also called "[[Def - (NAT) Network Address Translation|NAT]] overload," maps multiple private [[Def - (IP) Internet Protocol|IP]]s to a single public [[Def - (IP) Internet Protocol|IP]] by differentiating sessions via port numbers.

Key benefits of [[Def - (NAT) Network Address Translation|NAT]]:
- **Conserves public [[Def - (IP) Internet Protocol|IP]]s**: Extends the usable life of [[Def - (IPv4) Internet Protocol version 4|IPv4]].
- **Provides basic security**: Hides internal [[Def - (IP) Internet Protocol|IP]] structure from the outside world.
- **Simplifies network design**: Internal networks can reuse private address space.

However, [[Def - (NAT) Network Address Translation|NAT]] introduces complexity in certain applications, especially those requiring end-to-end connectivity or encryption, which is why **[[Def - (IPv6) Internet Protocol version 6|IPv6]]**, with its vast address space, eliminates the need for [[Def - (NAT) Network Address Translation|NAT]] altogether.
