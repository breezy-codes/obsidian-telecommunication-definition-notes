---
aliases:
  - Physical Layer
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
---

**Physical ([[Def - Physical (PHY) Layer|PHY]]) Layer** is the lowest layer (Layer 1) of the mobile network protocol stack, responsible for the actual transmission and reception of raw data bits over the wireless channel. It directly interfaces with the Radio Unit ([[Def - (RU) Radio Unit|RU]]) and the antenna system.

The [[Def - Physical (PHY) Layer|PHY]] layer converts data from higher layers into signals suitable for over-the-air transmission and vice versa. It performs tasks such as:
- **Modulation and demodulation**: Converts bits to waveforms and back.
- **Channel coding and decoding**: Adds redundancy for error correction.
- **Beamforming and MIMO processing**: Optimises signal direction and uses multiple antennas to enhance capacity and reliability.
- **Carrier aggregation and subcarrier mapping**: Organises the physical resources used in [[Def - (OFDMA) Orthogonal Frequency Division Multiple Access|OFDMA]]/[[Def - (SC-FDMA) Single Carrier Frequency Division Multiple Access|SC-FDMA]] schemes.

In a disaggregated [[Def - (RAN) Radio Access Network|RAN]], [[Def - Physical (PHY) Layer|PHY]] is split into lower [[Def - Physical (PHY) Layer|PHY]] (typically in the [[Def - (DU) Distributed Unit|DU]]) and upper [[Def - Physical (PHY) Layer|PHY]] (sometimes in the [[Def - (RU) Radio Unit|RU]]), depending on deployment and latency constraints.
