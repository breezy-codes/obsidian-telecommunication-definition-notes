---
aliases:
  - Port Address Translation
  - PAT
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Port Address Translation ([[Def - (PAT) Port Address Translation|PAT]])**, also known as **[[Def - (NAT) Network Address Translation|NAT]] Overload**, is a type of **Network Address Translation ([[Def - (NAT) Network Address Translation|NAT]])** that allows multiple devices on a private network to **share a single public [[Def - (IP) Internet Protocol|IP]] address** when accessing external networks such as the internet. It achieves this by mapping **each private [[Def - (IP) Internet Protocol|IP]] address and port number pair** to a **unique combination of the public [[Def - (IP) Internet Protocol|IP]] and a different port number**.

[[Def - (PAT) Port Address Translation|PAT]] operates at the **transport layer (Layer 4)** and modifies both the source [[Def - (IP) Internet Protocol|IP]] address and port number of outgoing packets. It maintains a **translation table** so that when response traffic returns, it can be forwarded to the correct internal host based on the port number.

How [[Def - (PAT) Port Address Translation|PAT]] works:
1. Multiple internal devices send packets to external destinations using the same public [[Def - (IP) Internet Protocol|IP]].
2. The router assigns a unique source port number to each outgoing connection.
3. Incoming responses are matched against the router’s [[Def - (PAT) Port Address Translation|PAT]] table and sent to the correct internal device and port.

Example:
- Private host A: `192.168.1.10:12345` → Public IP: `203.0.113.1:40001`
- Private host B: `192.168.1.20:12345` → Public IP: `203.0.113.1:40002`

Key benefits of [[Def - (PAT) Port Address Translation|PAT]]:
- **Conserves public [[Def - (IP) Internet Protocol|IP]] addresses**: Allows hundreds or thousands of devices to access the internet with a single public [[Def - (IP) Internet Protocol|IP]].
- **Simplifies [[Def - (IP) Internet Protocol|IP]] management**: Internal networks use private address space without requiring coordination with external address authorities.
- **Provides basic obfuscation**: Hides internal [[Def - (IP) Internet Protocol|IP]] structure from outside observers (though it is not a security mechanism).

Limitations:
- **Breaks some protocols**: Applications that embed IP or port info in payloads (e.g. SIP, FTP) may require additional helpers or fail to work through [[Def - (PAT) Port Address Translation|PAT]].
- **Outbound initiated only**: Inbound connections from the internet require manual port forwarding or cannot be established directly.

[[Def - (PAT) Port Address Translation|PAT]] is the **most common form of [[Def - (NAT) Network Address Translation|NAT]]** used in home routers, enterprise gateways, and firewalls, especially in [[Def - (IPv4) Internet Protocol version 4|IPv4]] networks constrained by limited public address space.
