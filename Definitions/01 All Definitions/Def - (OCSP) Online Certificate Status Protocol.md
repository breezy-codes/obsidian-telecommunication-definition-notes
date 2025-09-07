---
aliases:
  - Online Certificate Status Protocol
  - OCSP
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer7
---

**Online Certificate Status Protocol ([[Def - (OCSP) Online Certificate Status Protocol|OCSP]])** is a network protocol used to **query the revocation status of a digital certificate in real time**. It provides a more efficient and up-to-date alternative to **Certificate Revocation Lists ([[Def - (CRL) Certificate Revocation List|CRL]]s)** in **Public Key Infrastructure ([[Def - (PKI) Public Key Infrastructure|PKI]])** environments.

Instead of downloading a complete [[Def - (CRL) Certificate Revocation List|CRL]], a client sends a request to an **[[Def - (OCSP) Online Certificate Status Protocol|OCSP]] responder** (typically operated by the CA or a trusted third party) asking about the status of a specific certificate. The responder replies with one of the following:
- **Good**: The certificate is valid.
- **Revoked**: The certificate has been revoked.
- **Unknown**: The responder cannot determine the status.

Advantages of [[Def - (OCSP) Online Certificate Status Protocol|OCSP]]:
- **Low bandwidth**: Only queries the certificate in question.
- **Timely revocation checking**: Reduces delay between revocation and detection.
- **Digitally signed responses**: Ensure integrity and authenticity.

To improve performance and privacy, [[Def - (OCSP) Online Certificate Status Protocol|OCSP]] can be supplemented with **[[Def - (OCSP) Online Certificate Status Protocol|OCSP]] stapling**, where the server includes a pre-fetched [[Def - (OCSP) Online Certificate Status Protocol|OCSP]] response during the [[Def - (TLS) Transport Layer Security|TLS]] handshake, removing the need for clients to contact the [[Def - (OCSP) Online Certificate Status Protocol|OCSP]] responder directly.

[[Def - (OCSP) Online Certificate Status Protocol|OCSP]] is a critical component for maintaining trust in secure web communications, ensuring that compromised certificates cannot be used unnoticed.
