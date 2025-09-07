---
aliases:
  - Post Office Protocol version 3
  - POP3
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer7
---

**Post Office Protocol version 3 ([[Def - (POP3) Post Office Protocol version 3|POP3]])** is an **application-layer protocol** used to **retrieve email messages** from a remote mail server to a local email client. Defined in **RFC 1939**, [[Def - (POP3) Post Office Protocol version 3|POP3]] is designed for **offline email access**, where messages are typically downloaded and deleted from the server.

[[Def - (POP3) Post Office Protocol version 3|POP3]] works over:
- **Port 110**: Standard [[Def - (POP3) Post Office Protocol version 3|POP3]] connection.
- **Port 995**: POP3S ([[Def - (POP3) Post Office Protocol version 3|POP3]] over [[Def - (SSL) Secure Sockets Layer|SSL]]/[[Def - (TLS) Transport Layer Security|TLS]]) for encrypted retrieval.

Key characteristics:
- **Simple protocol**: Designed for single-device access with minimal server storage.
- **Local message storage**: Once retrieved, messages are stored and managed on the client side.
- **Limited synchronisation**: Changes made on the client (e.g. read/unread status) are not reflected across other devices.

While [[Def - (POP3) Post Office Protocol version 3|POP3]] is efficient and straightforward, it lacks the flexibility of **[[Def - (IMAP) Internet Message Access Protocol|IMAP]]**, making it less suited for multi-device access or modern email workflows. It is still used in lightweight systems and embedded email clients where local storage is preferred.
