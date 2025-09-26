---
aliases:
  - Radio Unit
  - RU
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Radio Unit ([[Def - (RU) Radio Unit|RU]])** is a fundamental component of the disaggregated [[Def - (RAN) Radio Access Network|RAN]] (Radio Access Network) architecture, particularly in 5G and [[Def - (O-RAN) Open Radio Access Network|O-RAN]] deployments. The [[Def - (RU) Radio Unit|RU]] is responsible for all radio frequency ([[Def - (RF) Radio Frequency|RF]]) related functions, including the transmission and reception of signals over the air interface to and from User Equipment ([[Def - (UE) User Equipment|UE]]).

It performs functions such as digital-to-analog conversion, [[Def - (RF) Radio Frequency|RF]] amplification, filtering, and beamforming. It interfaces with the Distributed Unit ([[Def - (DU) Distributed Unit|DU]]) via a [[Def - Fronthaul|fronthaul]] link using protocols like [[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]], and with the antenna array to provide coverage.

Key characteristics of the [[Def - (RU) Radio Unit|RU]]:
- **Located near or integrated with the antenna**: Reduces losses from long feeder cables.
- **Supports Massive MIMO ([[Def - (mMIMO) Massive MIMO|mMIMO]]) and [[Def - Beamforming|beamforming]]**: Enhances capacity and coverage.
- **Handles [[Def - (RF) Radio Frequency|RF]] processing and analog-digital conversion**: Allows for centralisation of baseband processing.

By offloading [[Def - (RF) Radio Frequency|RF]] tasks to the [[Def - (RU) Radio Unit|RU]], network operators can flexibly place the [[Def - (DU) Distributed Unit|DU]] and [[Def - (CU) Centralised Unit|CU]] in locations that balance cost, performance, and latency. This modular approach supports easier upgrades and vendor interoperability in multi-vendor [[Def - (O-RAN) Open Radio Access Network|O-RAN]] systems.
