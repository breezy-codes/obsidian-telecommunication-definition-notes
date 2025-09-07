---
aliases:
  - Non-Orthogonal Multiple Access
  - NOMA
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Non-Orthogonal Multiple Access ([[Def - (NOMA) Non-Orthogonal Multiple Access|NOMA]])** is a wireless access technique that allows multiple users to share the same time and frequency resources by distinguishing them through **power levels** or **unique codes**, rather than assigning each user a separate slot or channel.

In **power-domain [[Def - (NOMA) Non-Orthogonal Multiple Access|NOMA]]**, which is commonly studied for 5G, the base station transmits a composite signal containing messages for multiple users at different power levels. Users with **weaker signal conditions** (e.g. farther from the base station) are allocated more power, while those closer receive less. Each user then decodes their message using a technique called **Successive Interference Cancellation (SIC)**.

Key benefits of [[Def - (NOMA) Non-Orthogonal Multiple Access|NOMA]]:
- **Increased spectral efficiency**: More users can be supported on the same resource block.
- **Improved connectivity**: Useful for dense or heterogeneous networks with many devices.
- **Fairness**: Allows better service to users with weaker channels without sacrificing total throughput.

[[Def - (NOMA) Non-Orthogonal Multiple Access|NOMA]] breaks the traditional limit of one user per resource and is considered a key candidate for **massive access** in 5G and beyond, especially in applications like IoT, where supporting many simultaneous low-rate connections is crucial.
