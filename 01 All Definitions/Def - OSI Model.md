---
aliases:
  - OSI Model
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/standardisation-and-organisations
---

**OSI Model** (Open Systems Interconnection Model) is a conceptual framework that standardises the functions of a communication system into seven distinct layers. It was developed by the International Organisation for Standardisation (ISO) to help different networks and devices communicate with one another by using a common reference model.

Each layer of the [[Def - OSI Model|OSI Model]] has a specific role and communicates with the layers directly above and below it. The layers, from top to bottom, are:
1. **Application Layer**  
   Interfaces directly with user applications. It handles high-level protocols, user interfaces, and services such as email, file transfer, and web browsing.
2. **Presentation Layer**  
   Translates data between the application layer and the network. Responsible for data formatting, encryption, and compression.
3. **Session Layer**  
   Manages sessions or connections between applications. It establishes, maintains, and terminates communication sessions.
4. **Transport Layer**  
   Provides end-to-end communication, error recovery, and flow control. Protocols like [[Def - (TCP) Transmission Control Protocol|TCP]] and [[Def - (UDP) User Datagram Protocol|UDP]] operate at this layer.
5. **Network Layer**  
   Determines the best physical path for data. Handles logical addressing and routing, [[Def - (IP) Internet Protocol|IP]] (Internet Protocol) operates here.
6. **Data Link Layer**  
   Ensures reliable transmission over a single link. Manages [[Def - (MAC) Medium Access Control|MAC]] addresses, error detection, and framing, used by Ethernet and WiFi.
7. **Physical Layer**  
   Transmits raw bits over a physical medium. Defines hardware elements like cables, switches, voltage levels, and radio frequencies.

Key features of the [[Def - OSI Model|OSI Model]]:
- **Layered abstraction**: Breaks down complex networking tasks into manageable layers.
- **Interoperability**: Encourages standardisation, making it easier for different systems to work together.
- **Troubleshooting aid**: Helps network engineers isolate and diagnose issues by layer.