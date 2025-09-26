---
aliases:
  - Dynamic Host Configuration Protocol
  - DHCP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer7
---

**Dynamic Host Configuration Protocol ([[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]])** is a network management protocol used to **automatically assign [[Def - (IP) Internet Protocol|IP]] addresses and configuration parameters** (such as subnet mask, default gateway, and [[Def - (DNS) Domain Name System|DNS]] server) to devices on a network.

[[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] operates using a **client-server model**, where devices ([[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] clients) broadcast requests, and a central [[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] server responds with the necessary configuration.

Key steps in the [[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] lease process:
1. **DHCP Discover**: The client broadcasts a request for configuration.
2. **DHCP Offer**: The server responds with an available IP and parameters.
3. **DHCP Request**: The client requests to use the offered IP.
4. **DHCP Acknowledgement**: The server confirms and leases the address to the client.

[[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] simplifies network administration by:
- **Avoiding manual configuration**: Especially useful for large or dynamic environments.
- **Centralising management**: [[Def - (IP) Internet Protocol|IP]] pools, lease duration, and options can be adjusted from one location.
- **Supporting reuse**: Leases expire and [[Def - (IP) Internet Protocol|IP]]s are returned to the pool for reuse.

[[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] is commonly used in **[[Def - (IPv4) Internet Protocol version 4|IPv4]]** networks. In **[[Def - (IPv6) Internet Protocol version 6|IPv6]]**, DHCPv6 coexists with **[[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]]** and **[[Def - (NDP) Neighbour Discovery Protocol|NDP]]** for address assignment and configuration.
