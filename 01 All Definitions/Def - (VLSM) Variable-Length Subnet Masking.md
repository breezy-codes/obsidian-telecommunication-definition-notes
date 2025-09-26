---
aliases:
  - Variable-Length Subnet Masking
  - VLSM
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Variable-Length Subnet Masking ([[Def - (VLSM) Variable-Length Subnet Masking|VLSM]])** is a subnetting technique that allows network administrators to **divide an IP address space into subnets of different sizes**, optimising the use of available addresses. Unlike fixed-length subnetting, where all subnets are the same size, [[Def - (VLSM) Variable-Length Subnet Masking|VLSM]] enables the assignment of subnet masks tailored to the specific needs of each subnet.

[[Def - (VLSM) Variable-Length Subnet Masking|VLSM]] is sometimes referred to as "**subnetting a subnet**" and is a key enabler of **Classless Inter-Domain Routing ([[Def - (CIDR) Classless Inter-Domain Routing|CIDR]])**. It allows efficient [[Def - (IP) Internet Protocol|IP]] address planning by allocating only as many addresses as needed to each segment of a network.

Key features of [[Def - (VLSM) Variable-Length Subnet Masking|VLSM]]:
- **Customisable subnet sizes**: Large subnets for [[Def - (LAN) Local Area Network|LAN]]s, smaller ones for point-to-point links.
- **Improved address utilisation**: Minimises wasted addresses, especially in [[Def - (IPv4) Internet Protocol version 4|IPv4]].
- **Supports hierarchical addressing**: Useful for organising [[Def - (IP) Internet Protocol|IP]] spaces in complex networks.

Example:
Given a network `192.168.1.0/24`, you could allocate:
- `192.168.1.0/26` for a [[Def - (LAN) Local Area Network|LAN]] needing 62 hosts,
- `192.168.1.64/27` for another [[Def - (LAN) Local Area Network|LAN]] needing 30 hosts,
- `192.168.1.96/30` for a point-to-point link (2 hosts),
- and so on.

[[Def - (VLSM) Variable-Length Subnet Masking|VLSM]] requires the use of a **routing protocol that supports classless routing**, such as:
- [[Def - (OSPF) Open Shortest Path First|OSPF]]
- [[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]]
- [[Def - (RIP) Routing Information Protocol|RIP]] version 2
- [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]]

In summary, [[Def - (VLSM) Variable-Length Subnet Masking|VLSM]] provides the **flexibility and efficiency** needed for modern [[Def - (IP) Internet Protocol|IP]] addressing, especially in [[Def - (IPv4) Internet Protocol version 4|IPv4]] environments where address conservation is critical. It plays an essential role in both enterprise and [[Def - (ISP) Internet Service Provider|ISP]]-level [[Def - (IP) Internet Protocol|IP]] address planning.
