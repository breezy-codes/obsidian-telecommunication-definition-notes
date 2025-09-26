---
aliases:
  - Time Division Multiplexing Passive Optical Network
  - TDM-PON
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Time Division Multiplexing Passive Optical Network ([[Def - (TDM-PON) Time Division Multiplexing Passive Optical Network|TDM-PON]])** is a type of fibre access technology that uses **time division multiplexing** to allow multiple users to share a single optical fibre and central office device. It is commonly used in **[[Def - (FTTH) Fibre to the Home|FTTH]]** deployments to deliver broadband services to homes and businesses.

In a [[Def - (TDM-PON) Time Division Multiplexing Passive Optical Network|TDM-PON]], a single **Optical Line Terminal ([[Def - (OLT) Optical Line Terminal|OLT]])** at the provider’s central office communicates with multiple **Optical Network Units ([[Def - (ONU) Optical Network Unit|ONU]]s)** or **Optical Network Terminals ([[Def - (ONTs) Optical Network Terminals|ONT]]s)** at customer sites. The system uses one wavelength for downstream (provider to user) and one for upstream (user to provider) transmission.

- In the **downstream**, the [[Def - (OLT) Optical Line Terminal|OLT]] sends data to all [[Def - (ONU) Optical Network Unit|ONU]]s in broadcast mode, and each [[Def - (ONU) Optical Network Unit|ONU]] filters out the data meant for it.
- In the **upstream**, [[Def - (ONU) Optical Network Unit|ONU]]s take turns sending data during scheduled time slots assigned by the [[Def - (OLT) Optical Line Terminal|OLT]], avoiding collisions.

Key benefits of [[Def - (TDM-PON) Time Division Multiplexing Passive Optical Network|TDM-PON]]:
- **Efficient fibre usage**: Allows many users to share a single fibre and [[Def - (OLT) Optical Line Terminal|OLT]].
- **Passive architecture**: Uses splitters with no power requirement in the field, reducing maintenance and cost.
- **Mature standards**: Includes GPON, EPON, and XG-PON, widely deployed globally.

[[Def - (TDM-PON) Time Division Multiplexing Passive Optical Network|TDM-PON]] provides a scalable, low-cost way to deliver high-speed internet access, particularly in residential and small-business settings.
