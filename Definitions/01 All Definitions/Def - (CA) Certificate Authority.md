---
aliases:
  - Certificate Authority
  - CA
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer7
---

**Certificate Authority ([[Def - (CA) Certificate Authority|CA]])** is a trusted entity in a **Public Key Infrastructure ([[Def - (PKI) Public Key Infrastructure|PKI]])** responsible for issuing, digitally signing, and managing **digital certificates**. These certificates bind public keys to verified identities such as domain names, individuals, or organisations.

A [[Def - (CA) Certificate Authority|CA]] acts as a cornerstone of trust by verifying that an entity requesting a certificate is legitimate. Once verified, the [[Def - (CA) Certificate Authority|CA]] issues a **X.509 certificate** that includes the subject's public key, identity information, and the [[Def - (CA) Certificate Authority|CA]]’s digital signature.

Key functions of a [[Def - (CA) Certificate Authority|CA]]:
- **Certificate issuance**: Generates and signs certificates after validating the request.
- **Certificate revocation**: Maintains lists of revoked certificates (via [[Def - (CRL) Certificate Revocation List|CRL]] or [[Def - (OCSP) Online Certificate Status Protocol|OCSP]]).
- **Root and intermediate hierarchy**: Uses a **root [[Def - (CA) Certificate Authority|CA]]** to establish trust and **intermediate [[Def - (CA) Certificate Authority|CA]]s** to distribute responsibilities and improve security.
- **Trust anchor in browsers**: Root [[Def - (CA) Certificate Authority|CA]]s are pre-installed in operating systems and browsers, enabling [[Def - (TLS) Transport Layer Security|TLS]] and HTTPS trust chains.

[[Def - (CA) Certificate Authority|CA]]s play a central role in securing communication across the internet, enabling protocols such as **[[Def - (SSL) Secure Sockets Layer|SSL]]/[[Def - (TLS) Transport Layer Security|TLS]]**, **[[Def - (SMIME) SecureMultipurpose Internet Mail Extensions|S/MIME]]**, **[[Def - (IPsec) Internet Protocol Security|IPSec]]**, and **code signing**. Mismanagement or compromise of a [[Def - (CA) Certificate Authority|CA]] can undermine the security of the entire [[Def - (PKI) Public Key Infrastructure|PKI]] ecosystem.
