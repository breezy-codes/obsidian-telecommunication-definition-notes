---
aliases:
  - Transmission Time Interval
  - TTI
tags:
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/OSI-model/layer2
---

**Transmission Time Interval ([[Def - (TTI) Transmission Time Interval|TTI]])** is the smallest unit of time over which data is scheduled and transmitted on the air interface in mobile networks. It defines the granularity of transmission and influences system responsiveness and latency.

In **[[Def - (LTE) Long Term Evolution|LTE]]**, the standard [[Def - (TTI) Transmission Time Interval|TTI]] is **1 ms**, meaning data can be scheduled and updated every millisecond. In **[[Def - (5G-NR) 5G New Radio|5G-NR]]**, [[Def - (TTI) Transmission Time Interval|TTI]] is more flexible due to its **scalable numerology**, allowing shorter or longer [[Def - (TTI) Transmission Time Interval|TTI]]s (e.g. 0.125 ms or 0.25 ms), depending on the use case.

[[Def - (TTI) Transmission Time Interval|TTI]] types in 5G:
- **Fixed TTI**: Predefined duration (e.g. 1 ms).
- **Mini-slot TTI**: Shorter bursts used for low-latency communication.
- **Flexible TTI**: Dynamically adjusted based on service needs.

Key impacts of [[Def - (TTI) Transmission Time Interval|TTI]]:
- **Latency**: Shorter [[Def - (TTI) Transmission Time Interval|TTI]]s reduce delay for time-sensitive applications.
- **Scheduling efficiency**: Fine granularity enables more responsive and adaptive resource use.
- **Energy consumption**: [[Def - (TTI) Transmission Time Interval|TTI]] design affects how often devices need to wake up and transmit.

