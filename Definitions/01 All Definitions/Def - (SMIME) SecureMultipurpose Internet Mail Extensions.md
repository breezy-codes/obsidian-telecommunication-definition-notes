---
aliases:
  - Secure/Multipurpose Internet Mail Extensions
  - S/MIME
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer7
---

**Secure/Multipurpose Internet Mail Extensions ([[Def - (SMIME) SecureMultipurpose Internet Mail Extensions|S/MIME]])** is a standard for **securing email communication** using **public key cryptography**, defined by the [[Def - (IETF) Internet Engineering Task Force|IETF]]. It provides **end-to-end encryption**, **authentication**, **message integrity**, and **non-repudiation** by attaching digital signatures and enabling encryption at the message level.

[[Def - (SMIME) SecureMultipurpose Internet Mail Extensions|S/MIME]] is built on top of MIME, the standard format for email attachments, and integrates with **X.509 certificates** issued by trusted **Certificate Authorities ([[Def - (CA) Certificate Authority|CA]]s)**. Each user has a public-private key pair and a digital certificate that proves their identity.

[[Def - (SMIME) SecureMultipurpose Internet Mail Extensions|S/MIME]] supports two main security services:
- **Digital signing**: Ensures message authenticity and integrity by allowing recipients to verify the sender’s identity and detect tampering.
- **Encryption**: Protects message confidentiality by encrypting content using the recipient’s public key.

Advantages of [[Def - (SMIME) SecureMultipurpose Internet Mail Extensions|S/MIME]]:
- **Interoperability**: Widely supported in enterprise email clients like Outlook, Apple Mail, and Thunderbird.
- **Strong identity binding**: Certificates ensure that email originates from and is accessible only to verified users.
- **Enterprise-ready**: Integrates well with internal [[Def - (PKI) Public Key Infrastructure|PKI]] and global trust hierarchies.

Limitations include dependence on a [[Def - (PKI) Public Key Infrastructure|PKI]] infrastructure for certificate issuance and revocation management, and more complex setup compared to modern alternatives like PGP for personal email use.
