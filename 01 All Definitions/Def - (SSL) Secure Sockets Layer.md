---
aliases:
  - Secure Sockets Layer
  - SSL
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer6
  - telecommunications/OSI-model/layer7
---

**Secure Sockets Layer ([[Def - (SSL) Secure Sockets Layer|SSL]])** is a cryptographic protocol originally developed by Netscape to provide secure communication over the internet by encrypting data between clients and servers. [[Def - (SSL) Secure Sockets Layer|SSL]] was designed to protect confidentiality, integrity, and authenticity of data exchanged, especially for web traffic (e.g. HTTPS).

[[Def - (SSL) Secure Sockets Layer|SSL]] uses a **handshake mechanism** to establish a secure session:
1. The client initiates a handshake and receives the server’s certificate.
2. The server and client agree on encryption algorithms and session keys.
3. Encrypted communication begins once the handshake is complete.

Key features of [[Def - (SSL) Secure Sockets Layer|SSL]]:
- **Encryption**: Protects data from eavesdropping using symmetric and asymmetric algorithms.
- **Authentication**: Server certificates (and optionally client certificates) verify identities.
- **Integrity**: Ensures data hasn’t been altered in transit using message authentication codes (MACs).

Despite its historical importance, all versions of [[Def - (SSL) Secure Sockets Layer|SSL]] ([[Def - (SSL) Secure Sockets Layer|SSL]] 2.0 and [[Def - (SSL) Secure Sockets Layer|SSL]] 3.0) are now considered **deprecated** and insecure due to known vulnerabilities. Modern systems have fully transitioned to **[[Def - (TLS) Transport Layer Security|TLS]]**, the more secure successor protocol.
