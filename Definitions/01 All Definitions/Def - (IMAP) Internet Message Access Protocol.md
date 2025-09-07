---
aliases:
  - Internet Message Access Protocol
  - IMAP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer7
---

**Internet Message Access Protocol ([[Def - (IMAP) Internet Message Access Protocol|IMAP]])** is an **application-layer protocol** used by email clients to **retrieve and manage email** stored on a remote mail server. Unlike POP3, [[Def - (IMAP) Internet Message Access Protocol|IMAP]] is designed for **online and synchronised access**, allowing users to interact with their email across multiple devices while keeping messages stored centrally.

[[Def - (IMAP) Internet Message Access Protocol|IMAP]] operates over:
- **Port 143**: Standard port (optionally secured via STARTTLS).
- **Port 993**: IMAPS – secure [[Def - (IMAP) Internet Message Access Protocol|IMAP]] over [[Def - (SSL) Secure Sockets Layer|SSL]]/[[Def - (TLS) Transport Layer Security|TLS]].

Key features of [[Def - (IMAP) Internet Message Access Protocol|IMAP]]:
- **Server-based storage**: Emails remain on the server, accessible from multiple devices.
- **Message synchronisation**: Flags (e.g. read/unread), folders, and message states sync across clients.
- **Partial download**: Clients can retrieve headers or specific parts of messages on demand.
- **Folder support**: Enables creation and management of mail folders remotely.

[[Def - (IMAP) Internet Message Access Protocol|IMAP]] supports modern workflows such as:
- Reading an email on one device, and having it marked as read on others.
- Accessing email from multiple clients without duplicating or deleting messages locally.

[[Def - (IMAP) Internet Message Access Protocol|IMAP]] is widely used in **enterprise** and **consumer** email systems and is often paired with **SMTP** for sending mail.
