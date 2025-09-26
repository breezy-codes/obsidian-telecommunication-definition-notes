---
aliases:
  - Registration Authority
  - RA
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer7
---

**Registration Authority ([[Def - (RA) Registration Authority|RA]])** is an entity within a **Public Key Infrastructure ([[Def - (PKI) Public Key Infrastructure|PKI]])** that is responsible for **verifying the identity of certificate applicants** before certificates are issued by a **Certificate Authority ([[Def - (CA) Certificate Authority|CA]])**. The [[Def - (RA) Registration Authority|RA]] serves as a front-end to the [[Def - (CA) Certificate Authority|CA]], delegating the identity validation process while leaving the actual certificate generation and signing to the [[Def - (CA) Certificate Authority|CA]].

The RA does not issue certificates itself but plays a critical role in the **certificate lifecycle**:
- **Identity validation**: Confirms the legitimacy of a certificate request (e.g. ownership of a domain or the identity of a person or device).
- **Approval/rejection**: Forwards validated requests to the [[Def - (CA) Certificate Authority|CA]] or rejects suspicious ones.
- **Credential management**: May also assist in key generation, renewal, or recovery depending on policy.

Benefits of using an [[Def - (RA) Registration Authority|RA]]:
- **Scalability**: Distributes the workload of identity checking across multiple locations or organisations.
- **Security**: Separates verification duties from certificate signing, reducing the attack surface on the [[Def - (CA) Certificate Authority|CA]].
- **Custom validation policies**: Can enforce sector- or enterprise-specific identity checks before certificate issuance.

In large or federated environments (e.g. government, education), [[Def - (RA) Registration Authority|RA]]s are essential for delegating trust while maintaining a centralised root of authority.
