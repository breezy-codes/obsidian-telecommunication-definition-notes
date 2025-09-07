---
aliases:
  - Public Key Infrastructure
  - PKI
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer7
---

**Public Key Infrastructure ([[Def - (PKI) Public Key Infrastructure|PKI]])** is a framework of policies, technologies, and procedures used to manage **digital certificates** and **public-key encryption** in order to provide secure communication over untrusted networks like the internet. [[Def - (PKI) Public Key Infrastructure|PKI]] underpins security protocols such as [[Def - (TLS) Transport Layer Security|TLS]]/[[Def - (SSL) Secure Sockets Layer|SSL]], digital signatures, and secure email.

At its core, PKI uses **asymmetric cryptography**, involving a pair of mathematically related keys:
- **Public key**: Shared with others to encrypt data or verify digital signatures.
- **Private key**: Kept secret by the owner to decrypt data or create signatures.

Core components of PKI:
- **Certificate Authority ([[Def - (CA) Certificate Authority|CA]])**: A trusted entity that issues and signs digital certificates to bind public keys to verified identities (e.g. domain names or users).
- **Registration Authority ([[Def - (RA) Registration Authority|RA]])**: Validates the identity of certificate requesters on behalf of the [[Def - (CA) Certificate Authority|CA]].
- **Digital Certificate**: An electronic document that includes the public key, identity information, and [[Def - (CA) Certificate Authority|CA]] signature.
- **Certificate Revocation List ([[Def - (CRL) Certificate Revocation List|CRL]])** and **Online Certificate Status Protocol ([[Def - (OCSP) Online Certificate Status Protocol|OCSP]])**: Used to check whether certificates are still valid.

PKI enables:
- **Authentication**: Ensuring entities are who they claim to be.
- **Encryption**: Securing communication by allowing others to encrypt messages using a recipient’s public key.
- **Integrity**: Digital signatures verify that content has not been altered.

[[Def - (PKI) Public Key Infrastructure|PKI]] is critical for securing modern applications, including HTTPS websites, [[Def - (VPN) Virtual Private Network|VPN]]s, software code signing, and secure device provisioning.
