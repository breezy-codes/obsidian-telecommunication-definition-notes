---
aliases:
  - Single Carrier Frequency Division Multiple Access
  - SC-FDMA
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Single Carrier Frequency Division Multiple Access ([[Def - (SC-FDMA) Single Carrier Frequency Division Multiple Access|SC-FDMA]])** is a wireless transmission technique used primarily in the **uplink** of [[Def - (LTE) Long Term Evolution|LTE]] networks, where devices like smartphones send data back to the network. It combines the benefits of single-carrier transmission with frequency domain processing, offering a good balance between performance and power efficiency.

Unlike [[Def - (OFDMA) Orthogonal Frequency Division Multiple Access|OFDMA]], where users transmit over multiple subcarriers independently, [[Def - (SC-FDMA) Single Carrier Frequency Division Multiple Access|SC-FDMA]] spreads each user’s data across subcarriers in a way that results in a single-carrier signal. This reduces the **Peak-to-Average Power Ratio ([[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]])**, which is important for battery-powered devices because it allows more efficient use of the power amplifier.

[[Def - (SC-FDMA) Single Carrier Frequency Division Multiple Access|SC-FDMA]] works by applying a Discrete Fourier Transform (DFT) to the user's signal before transmission, followed by standard [[Def - (OFDM) Orthogonal Frequency Division Multiplexing|OFDM]] processing. At the receiver, the inverse process reconstructs the signal.

Key benefits of [[Def - (SC-FDMA) Single Carrier Frequency Division Multiple Access|SC-FDMA]]:
- **Lower PAPR**: Reduces power consumption and extends battery life in mobile devices.
- **Multi-path resilience**: Benefits from frequency domain equalisation, improving reliability in complex environments.
- **Efficient uplink access**: Makes it possible to support many users transmitting to the base station simultaneously.

[[Def - (SC-FDMA) Single Carrier Frequency Division Multiple Access|SC-FDMA]] is used in [[Def - (LTE) Long Term Evolution|LTE]]'s uplink to meet the energy efficiency needs of user equipment, while [[Def - (OFDMA) Orthogonal Frequency Division Multiple Access|OFDMA]] is used in the downlink for its flexibility and high data rate support.
