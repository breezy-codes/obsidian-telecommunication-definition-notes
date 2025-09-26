---
aliases:
  - Time Division Multiple Access
  - TDMA
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---
**Time Division Multiple Access ([[Def - (TDMA) Time Division Multiple Access|TDMA]])** is a **channel access method** that enables multiple users or devices to share the same frequency band by dividing communication time into **distinct, repeating time slots**. Each user is assigned a specific slot during which it can transmit or receive data, ensuring that multiple transmissions do not overlap.

[[Def - (TDMA) Time Division Multiple Access|TDMA]] is built on the principle of **Time Division Multiplexing ([[Def - (TDM) Time Division Multiplexing|TDM]])**, but is specifically focused on enabling multiple access — i.e. allowing many users to access the same channel without interfering with each other.

In a [[Def - (TDMA) Time Division Multiple Access|TDMA]] system:
- A **frame** is divided into several time slots.
- Each user or device is allocated one or more of these slots per frame.
- The process repeats cyclically, with each user getting consistent, scheduled access to the channel.

[[Def - (TDMA) Time Division Multiple Access|TDMA]] is commonly used in:
- **2G mobile networks**: Such as GSM, where users share a single carrier frequency via assigned time slots.
- **Satellite communications**: Where precise timing ensures efficient uplink/downlink scheduling.
- **Trunked radio systems**: For emergency services and fleet communication.

Advantages of [[Def - (TDMA) Time Division Multiple Access|TDMA]]:
- **Deterministic access**: Each device knows exactly when it can transmit, reducing collisions.
- **Efficient bandwidth use**: Ideal for applications with predictable data patterns.
- **Simplified hardware requirements**: Compared to spread-spectrum systems.

Limitations of [[Def - (TDMA) Time Division Multiple Access|TDMA]]:
- **Rigid allocation**: Inefficient when traffic is bursty or users are idle.
- **Strict timing synchronisation**: Requires accurate clocks and time coordination across devices.
- **Scalability**: Limited number of time slots per frame restricts simultaneous users.

TDMA differs from **[[Def - (CDMA) Code Division Multiple Access|CDMA]]** and **[[Def - (FDMA) Frequency Division Multiple Access|FDMA]]** in that it divides access **in time** rather than by code or frequency. It laid the foundation for early mobile systems and remains relevant in specific use cases where simplicity and deterministic scheduling are important.
