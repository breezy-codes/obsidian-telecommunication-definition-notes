---
aliases:
  - Time Division Multiplexing
  - TDM
tags:
  - telecommunications/definitions/multiplexing-and-modulation
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Time Division Multiplexing ([[Def - (TDM) Time Division Multiplexing|TDM]])** is a technique used in communication systems to transmit multiple signals over a single communication channel by dividing time into slots and assigning each signal a specific time slot in a repeating sequence. Each signal uses the full bandwidth of the channel, but only for a brief, allocated moment.

In [[Def - (TDM) Time Division Multiplexing|TDM]], the transmitter rapidly switches between multiple input signals, sending small portions of each one in turn. The receiver, knowing the timing structure, reconstructs each signal by extracting the data from its assigned time slots.

There are two main types of [[Def - (TDM) Time Division Multiplexing|TDM]]:
- **Synchronous [[Def - (TDM) Time Division Multiplexing|TDM]]**: Each signal is assigned a fixed time slot whether it has data to send or not. This can lead to inefficiencies if some sources are idle.
- **Asynchronous or Statistical [[Def - (TDM) Time Division Multiplexing|TDM]]**: Time slots are dynamically allocated based on demand, making better use of available bandwidth.

[[Def - (TDM) Time Division Multiplexing|TDM]] is commonly used in:
- **Telephony**: Traditional digital telephone systems use [[Def - (TDM) Time Division Multiplexing|TDM]] to combine multiple voice calls onto a single transmission line.
- **Optical networks**: Some passive optical networks (like GPON) use [[Def - (TDM) Time Division Multiplexing|TDM]] for upstream and downstream traffic sharing.
- **Satellite and microwave links**: Efficient for sharing expensive or limited-bandwidth links among multiple data streams.

Advantages of [[Def - (TDM) Time Division Multiplexing|TDM]]:
- **Efficient channel usage**: Especially when combined with statistical allocation.
- **Simple implementation**: Easy to synchronise when using fixed slot patterns.
- **Supports digital and analogue signals**: Widely applicable across different systems.

[[Def - (TDM) Time Division Multiplexing|TDM]] forms the basis for many foundational networking and telecommunication systems, enabling multiple users or services to share a single medium without interference.
