---
aliases:
  - Certificate Revocation List
  - CRL
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer7
---

**Certificate Revocation List ([[Def - (CRL) Certificate Revocation List|CRL]])** is a **digitally signed list** published by a **Certificate Authority ([[Def - (CA) Certificate Authority|CA]])** that identifies **digital certificates that have been revoked** before their scheduled expiration. A [[Def - (CRL) Certificate Revocation List|CRL]] is used in **Public Key Infrastructure ([[Def - (PKI) Public Key Infrastructure|PKI]])** to ensure that relying parties do not trust certificates that are no longer valid.

Reasons for revocation may include:
- Compromise of a private key.
- Change in the certificate holder’s status (e.g. leaving an organisation).
- Detection of fraud or misuse.

Key features of [[Def - (CRL) Certificate Revocation List|CRL]]s:
- **Issued at regular intervals**: To reflect up-to-date revocation status.
- **Contains serial numbers**: Of revoked certificates, along with revocation dates and reasons.
- **Signed by the [[Def - (CA) Certificate Authority|CA]]**: To prevent tampering and ensure authenticity.
- **Retrieved by clients**: During certificate validation, if configured to do so.

Limitations of [[Def - (CRL) Certificate Revocation List|CRL]]s:
- **Latency**: Clients may rely on outdated lists until the next update.
- **Performance impact**: Downloading large [[Def - (CRL) Certificate Revocation List|CRL]]s can slow validation, especially for resource-constrained devices.

Due to these limitations, **[[Def - (OCSP) Online Certificate Status Protocol|OCSP]]** was developed to provide more timely revocation checks in real time.
