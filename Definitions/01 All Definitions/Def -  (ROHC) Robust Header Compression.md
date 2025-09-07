---
aliases:
  - Robust Header Compression
  - ROHC
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**Robust Header Compression ([[Def -  (ROHC) Robust Header Compression|ROHC]])** is a header compression protocol used in wireless and cellular networks such as [[Def - (LTE) Long Term Evolution|LTE]] and 5G to reduce the overhead of IP-based communications. It is particularly effective for real-time services like Voice over IP ([[Def - (VoIP) Voice over Internet Protocol|VoIP]]), where repeated transmission of similar header information (e.g., [[Def - (IP) Internet Protocol|IP]]/[[Def - (UDP) User Datagram Protocol|UDP]]/[[Def - (RTP) Real-time Transport Protocol|RTP]]) can lead to significant inefficiencies.

[[Def -  (ROHC) Robust Header Compression|ROHC]] compresses headers in protocols such as [[Def - (IP) Internet Protocol|IP]], [[Def - (UDP) User Datagram Protocol|UDP]], and [[Def - (RTP) Real-time Transport Protocol|RTP]], minimising the number of bytes required to transmit each packet. This is crucial for improving spectral efficiency and conserving bandwidth, especially in environments with limited radio resources.

The key features of [[Def -  (ROHC) Robust Header Compression|ROHC]] include:
- **Efficiency**: Compresses headers from around 40–60 bytes down to 1–3 bytes in steady state, significantly reducing overhead.
- **Robustness**: Designed to handle wireless link characteristics such as packet loss and varying delays without needing retransmissions.
- **Context maintenance**: Maintains a context for each flow, enabling it to rebuild full headers at the decompression end with minimal signalling.

[[Def -  (ROHC) Robust Header Compression|ROHC]] operates at the [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] layer in the radio protocol stack, above the [[Def - (RLC) Radio Link Control|RLC]] layer. By reducing header size, it allows more efficient use of the air interface and improves user experience in mobile networks.
