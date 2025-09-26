---
aliases:
  - Transport Layer Security
  - TLS
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer6
  - telecommunications/OSI-model/layer7
---

**Transport Layer Security ([[Def - (TLS) Transport Layer Security]])** is the modern cryptographic protocol that replaced [[Def - (SSL) Secure Sockets Layer|SSL]] for securing communication over a network. It is widely used to protect data in transit across applications such as web browsing (HTTPS), email ([[Def - (IMAP) Internet Message Access Protocol|IMAP]]S/[[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]]), voice ([[Def - (VoIP) Voice over Internet Protocol|VoIP]]), and [[Def - (VPN) Virtual Private Network|VPN]]s.

[[Def - (TLS) Transport Layer Security|TLS]] operates at the transport layer and provides:
- **Confidentiality**: Encrypts data using symmetric encryption.
- **Integrity**: Detects tampering using MACs.
- **Authentication**: Verifies server identity using certificates and public key infrastructure ([[Def - (PKI) Public Key Infrastructure|PKI]]).

[[Def - (TLS) Transport Layer Security|TLS]] sessions begin with a **handshake** process that negotiates cryptographic parameters:
1. The client and server exchange capabilities and select cipher suites.
2. The server provides a digital certificate to prove its identity.
3. Session keys are securely generated and exchanged.
4. Encrypted communication begins.

Key advancements over [[Def - (SSL) Secure Sockets Layer|SSL]]:
- **Improved security**: Removes insecure algorithms and fixes protocol-level flaws.
- **Forward secrecy**: Prevents past communications from being decrypted if long-term keys are compromised.
- **Extensibility**: Supports a wide range of extensions and updates (e.g. ALPN for HTTP/2).

The current version, **TLS 1.3**, streamlines the handshake and eliminates outdated cryptographic methods, offering faster and more secure connections.
