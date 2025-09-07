---
aliases:
  - Software Defined Optical Networking
  - SDON
tags:
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/cross-layer
---

**Software Defined Optical Networking ([[Def - (SDON) Software Defined Optical Networking|SDON]])** is the application of Software Defined Networking ([[Def - (SDN) Software Defined Networking|SDN]]) principles to optical networks. It decouples the control plane from the underlying optical hardware, enabling centralised and programmable management of optical transport systems such as [[Def - (WDM) Wavelength Division Multiplexing|WDM]], [[Def - (OTN) Optical Transport Network|OTN]], and [[Def - (ROADM) Reconfigurable Optical Add-Drop Multiplexer|ROADM]]-based networks.

In traditional optical networks, configuration and management are often manual, vendor-specific, and rigid. [[Def - (SDON) Software Defined Optical Networking|SDON]] introduces an [[Def - (SDN) Software Defined Networking|SDN]] controller that communicates with optical devices using standardised interfaces (like NETCONF or OpenFlow extensions), allowing for real-time monitoring, path setup, failure recovery, and resource optimisation.

A typical [[Def - (SDON) Software Defined Optical Networking|SDON]] architecture includes:
- **Application layer**: Services and network functions that request specific bandwidth, latency, or path requirements.
- **Control layer**: The [[Def - (SDN) Software Defined Networking|SDN]] controller, extended to manage optical parameters like wavelength, modulation format, and power levels.
- **Optical infrastructure layer**: [[Def - (WDM) Wavelength Division Multiplexing|WDM]] systems, [[Def - (ROADM) Reconfigurable Optical Add-Drop Multiplexer|ROADM]]s, optical amplifiers, and transponders.

Benefits of [[Def - (SDON) Software Defined Optical Networking|SDON]] include:
- **Dynamic provisioning**: Light-paths can be set up, changed, or torn down automatically based on demand.
- **Cross-layer coordination**: Integrates with [[Def - (IP) Internet Protocol|IP]] and transport layers for end-to-end service control.
- **Improved utilisation**: Optimises use of wavelengths and reduces over-provisioning.
- **Faster recovery**: Enables rapid rerouting in case of faults or congestion.

[[Def - (SDON) Software Defined Optical Networking|SDON]] enables more agile and cost-effective optical networks, particularly in data centre interconnects, metro networks, and core transport systems.
