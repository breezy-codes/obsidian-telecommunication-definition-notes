---
aliases:
  - Duplicate Address Detection
  - DAD
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Duplicate Address Detection ([[Def - (DAD) Duplicate Address Detection|DAD]])** is a process used in **[[Def - (IPv6) Internet Protocol version 6|IPv6]]** networks to ensure that a newly assigned **[[Def - (IPv6) Internet Protocol version 6|IPv6]] address is unique** on the local link before it is used. It is a critical part of **Stateless Address Autoconfiguration ([[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]])** and also applies when manually configuring [[Def - (IPv6) Internet Protocol version 6|IPv6]] addresses.

[[Def - (DAD) Duplicate Address Detection|DAD]] works by:
1. Sending a **Neighbour Solicitation (NS)** message to the address being claimed.
2. Listening for a **Neighbour Advertisement (NA)** from any device that already uses the address.
3. If no response is received within a set time, the address is considered unique and is assigned.

If a response is received:
- The address is already in use, and the host **must not assign it** to itself.
- Depending on configuration, the host may generate a new address or report an error.

Key characteristics of [[Def - (DAD) Duplicate Address Detection|DAD]]:
- **Prevents address conflicts**: Ensures stable and predictable [[Def - (IPv6) Internet Protocol version 6|IPv6]] behaviour on shared networks.
- **Performed automatically**: Integrated into [[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]] and DHCPv6 address assignment.
- **Applies to link-local and global unicast addresses**: Any newly formed [[Def - (IPv6) Internet Protocol version 6|IPv6]] address must pass [[Def - (DAD) Duplicate Address Detection|DAD]] before being used.

[[Def - (DAD) Duplicate Address Detection|DAD]] is part of the **Neighbour Discovery Protocol ([[Def - (NDP) Neighbour Discovery Protocol|NDP]])** and helps maintain the integrity and reliability of [[Def - (IPv6) Internet Protocol version 6|IPv6]] communication by eliminating duplicate address assignments at the link level.
