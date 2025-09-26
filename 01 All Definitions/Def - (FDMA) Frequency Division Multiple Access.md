---
aliases:
  - Frequency Division Multiple Access
  - FDMA
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Frequency Division Multiple Access ([[Def - (FDMA) Frequency Division Multiple Access|FDMA]])** is a **multiple access technique** in which the available bandwidth of a communication channel is **divided into separate frequency bands**, with each user or device assigned a unique frequency band for the duration of their connection. This allows multiple users to transmit simultaneously without interfering with one another, as each operates on a distinct portion of the spectrum.

[[Def - (FDMA) Frequency Division Multiple Access|FDMA]] is based on the underlying principle of **Frequency Division Multiplexing ([[Def - (FDM) Frequency Division Multiplexing|FDM]])**, but specifically applies to user access in shared communication systems.

In an [[Def - (FDMA) Frequency Division Multiple Access|FDMA]] system:
- The channel is divided into **non-overlapping frequency sub-channels**.
- Each user is **permanently assigned** one sub-channel for the duration of their session.
- Guard bands are placed between frequencies to prevent **inter-channel interference**.

[[Def - (FDMA) Frequency Division Multiple Access|FDMA]] is commonly used in:
- **1G analog mobile networks**: Such as AMPS, where each call had a dedicated frequency.
- **Satellite communications**: For allocating uplink/downlink bands to different earth stations.
- **Radio broadcasting**: Where each station transmits on a unique frequency.

Advantages of [[Def - (FDMA) Frequency Division Multiple Access|FDMA]]:
- **Simplicity**: Easy to implement using analogue or digital filtering.
- **Continuous transmission**: Users can transmit at any time without waiting for a time slot.
- **Low latency**: Suitable for applications needing steady, uninterrupted bandwidth.

Limitations of [[Def - (FDMA) Frequency Division Multiple Access|FDMA]]:
- **Inflexibility**: Bandwidth is statically allocated even if a user is idle, leading to inefficient use.
- **Limited number of users**: The number of available frequencies restricts how many users can be supported.
- **Guard band overhead**: Reduces spectral efficiency due to the need for separation between sub-channels.

[[Def - (FDMA) Frequency Division Multiple Access|FDMA]] contrasts with **[[Def - (TDMA) Time Division Multiple Access|TDMA]]**, which divides access in **time**, and **[[Def - (CDMA) Code Division Multiple Access|CDMA]]**, which separates users via **spreading codes**. While largely replaced in modern digital systems, FDMA concepts persist in systems like radio, satellite, and some IoT networks where simplicity and dedicated bandwidth are preferred.
