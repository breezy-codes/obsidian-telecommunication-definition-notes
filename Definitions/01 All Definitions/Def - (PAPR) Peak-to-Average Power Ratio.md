---
aliases:
  - Peak-to-Average Power Ratio
  - PAPR
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer1
---

**Peak-to-Average Power Ratio ([[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]])** is a key metric used in wireless communication systems to quantify the **ratio of the peak signal power to its average power**. It is especially relevant in **multicarrier modulation schemes** such as **[[Def - (OFDM) Orthogonal Frequency Division Multiplexing|OFDM]] (Orthogonal Frequency Division Multiplexing)**, where multiple subcarriers are combined to form the transmitted signal.

[[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]] is defined mathematically as:

$$
\text{PAPR} = \frac{\max |x(t)|^2}{\mathbb{E}[|x(t)|^2]}
$$

Where:
- $\max |x(t)|^2$ is the maximum instantaneous power of the signal.
- $\mathbb{E}[|x(t)|^2]$ is the average power over time.

High [[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]] means that the signal occasionally reaches **very high peaks** relative to its average level. This poses challenges for **power amplifiers** and **analog front ends**, which must be capable of handling these peaks without distortion (nonlinear behaviour), often requiring **back-off** from saturation levels—thus reducing power efficiency.

Key issues and implications of high [[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]]:
- **Amplifier inefficiency**: High [[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]] forces amplifiers to operate in a less efficient linear region.
- **Increased cost and power consumption**: Hardware must be overdesigned to avoid clipping or distortion.
- **Signal distortion**: Nonlinear effects can introduce spectral regrowth and bit errors.

Common mitigation techniques:
- **Clipping and filtering**
- **Selective mapping (SLM)**
- **Tone reservation**
- **Coding techniques**
- **Partial transmit sequences (PTS)**

[[Def - (PAPR) Peak-to-Average Power Ratio|PAPR]] is a critical design consideration in systems like **[[Def - (LTE) Long Term Evolution|LTE]]**, **[[Def - (5G-NR) 5G New Radio|5G-NR]]**, **WiFi**, and **digital broadcasting**, where multicarrier signals are widely used due to their spectral efficiency and robustness against multi-path fading.
