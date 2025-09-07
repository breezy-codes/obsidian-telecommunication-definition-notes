---
aliases:
  - Domain Name System
  - DNS
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer7
---

**Domain Name System ([[Def - (DNS) Domain Name System|DNS]])** is a hierarchical and decentralised naming system that translates **human-readable domain names** (e.g. `www.example.com`) into **[[Def - (IP) Internet Protocol|IP]] addresses** (e.g. `93.184.216.34`), which are required for locating and identifying devices on [[Def - (IP) Internet Protocol|IP]] networks. [[Def - (DNS) Domain Name System|DNS]] acts as the **“phone-book of the internet,”** enabling users to access websites and services using easily remembered names instead of numeric addresses.

[[Def - (DNS) Domain Name System|DNS]] operates on a **client-server model**, with recursive and authoritative [[Def - (DNS) Domain Name System|DNS]] servers working together to resolve queries. The process begins when a client (like a web browser) requests the [[Def - (IP) Internet Protocol|IP]] address for a domain name.

The resolution process typically involves:
1. **DNS Resolver (Recursive Resolver)**: The client sends a query to the resolver, which takes responsibility for resolving the name.
2. **Root Name Server**: Directs the resolver to the appropriate Top-Level Domain (TLD) server.
3. **TLD Name Server**: Provides the address of the authoritative name server for the requested domain.
4. **Authoritative Name Server**: Returns the IP address of the domain or a CNAME (alias) record.

Core record types used in DNS:
- **A record**: Maps a domain to an IPv4 address.
- **AAAA record**: Maps a domain to an IPv6 address.
- **CNAME**: Alias of another domain name.
- **MX record**: Specifies mail servers for a domain.
- **NS record**: Indicates authoritative name servers.
- **TXT**: Holds descriptive text, often used for SPF, DKIM, and verification.

Key DNS features:
- **Caching**: Resolvers cache results to reduce lookup time and network load.
- **TTL (Time to Live)**: Determines how long a DNS record is cached.
- **DNSSEC (Security Extensions)**: Adds cryptographic signatures to prevent spoofing and tampering.
- **Reverse DNS**: Maps IP addresses back to domain names using PTR records.

DNS uses **UDP port 53** for most queries and **TCP port 53** for zone transfers and larger responses.

As a fundamental service in internet and private networks, DNS supports everything from website access to email delivery, CDNs, IoT devices, and enterprise applications.