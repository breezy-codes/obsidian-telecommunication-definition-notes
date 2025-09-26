---
aliases:
  - File Transfer Protocol
  - FTP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/OSI-model/layer7
---

**File Transfer Protocol ([[Def - (FTP) File Transfer Protocol|FTP]])** is a standard **application-layer protocol** used for **transferring files between systems** over a [[Def - (TCP) Transmission Control Protocol|TCP]]/[[Def - (IP) Internet Protocol|IP]] network. Defined in **RFC 959**, [[Def - (FTP) File Transfer Protocol|FTP]] allows users to upload, download, rename, delete, and manage files on a remote server.

[[Def - (FTP) File Transfer Protocol|FTP]] operates using two separate connections:
- **Control connection** ([[Def - (TCP) Transmission Control Protocol|TCP]] port 21): For sending commands and responses.
- **Data connection** (usually [[Def - (TCP) Transmission Control Protocol|TCP]] port 20): For transferring file content.

Modes of operation:
- **Active mode**: Server initiates data connection to the client.
- **Passive mode**: Client initiates both connections; preferred when client is behind a firewall or [[Def - (NAT) Network Address Translation|NAT]].

Key features:
- **Authentication**: Supports anonymous and user-authenticated sessions.
- **Directory navigation**: Users can browse and manipulate files and folders remotely.
- **ASCII and binary modes**: Supports text and raw data transfers.

Security concerns:
- **Unencrypted by default**: Credentials and files are sent in plaintext.
- **FTPS ([[Def - (FTP) File Transfer Protocol|FTP]] Secure)**: Adds [[Def - (SSL) Secure Sockets Layer|SSL]]/[[Def - (TLS) Transport Layer Security|TLS]] encryption to standard [[Def - (FTP) File Transfer Protocol|FTP]].
- **SFTP (SSH File Transfer Protocol)**: A completely separate protocol using SSH, often confused with [[Def - (FTP) File Transfer Protocol|FTP]] but more secure.

[[Def - (FTP) File Transfer Protocol|FTP]] is still used for transferring large files, software updates, and backups, though it is increasingly being replaced by secure alternatives.
