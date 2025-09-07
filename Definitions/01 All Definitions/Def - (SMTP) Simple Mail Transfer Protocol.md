---
aliases:
  - Simple Mail Transfer Protocol
  - SMTP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/OSI-model/layer7
---

**Simple Mail Transfer Protocol ([[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]])** is an **application-layer protocol** used for **sending and relaying email messages** between mail servers. Defined in **RFC 5321**, SMTP is the standard protocol for email transmission across the internet.

SMTP works as a **push protocol**: it transfers email from the sender's client (Mail User Agent, or MUA) to the recipient’s mail server (Mail Transfer Agent, or MTA), and also between MTAs. It does **not retrieve** email from a mailbox; this is handled by protocols like **[[Def - (IMAP) Internet Message Access Protocol|IMAP]]** or **[[Def - (POP3) Post Office Protocol version 3|POP3]]**.

SMTP functions over:
- **Port 25**: Server-to-server transmission (original standard, often blocked by ISPs for spam prevention).
- **Port 587**: Secure submission by mail clients (with STARTTLS encryption).
- **Port 465**: Legacy secure [[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]] (SMTPS).

Key features:
- **Plain-text protocol**: Commands like `HELO`, `MAIL FROM`, `RCPT TO`, and `DATA`.
- **Supports extensions**: e.g., `STARTTLS` for encryption, `AUTH` for login mechanisms.
- **Store-and-forward model**: Ensures reliable message delivery through retries and queuing.

[[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]] is widely used in conjunction with other protocols to provide a complete email service:
- **[[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]]**: Sending mail.
- **[[Def - (IMAP) Internet Message Access Protocol|IMAP]]/[[Def - (POP3) Post Office Protocol version 3|POP3]]**: Retrieving mail.

Because [[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]] transmits messages in plaintext by default, **encryption via [[Def - (TLS) Transport Layer Security|TLS]]** is recommended for privacy and security.
