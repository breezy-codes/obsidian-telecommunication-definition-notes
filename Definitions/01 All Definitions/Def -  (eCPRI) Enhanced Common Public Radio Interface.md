---
aliases:
  - Enhanced Common Public Radio Interface
  - eCPRI
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Enhanced Common Public Radio Interface ([[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]])** is a fronthaul protocol developed to address the bandwidth and flexibility limitations of the original [[Def - (CPRI) Common Public Radio Interface|CPRI]] standard. It is used to connect the Distributed Unit ([[Def - (DU) Distributed Unit|DU]]) and the Radio Unit ([[Def - (RU) Radio Unit|RU]]) in disaggregated [[Def - (RAN) Radio Access Network|RAN]] architectures, such as in [[Def - (O-RAN) Open Radio Access Network|O-RAN]] and 5G deployments.

Unlike traditional [[Def - (CPRI) Common Public Radio Interface|CPRI]], which transmits digitised radio samples over dedicated point-to-point links, [[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]] is packet-based and typically runs over Ethernet or [[Def - (IP) Internet Protocol|IP]] networks. This allows for better scalability, cost-efficiency, and integration with standard transport technologies.

Key features of [[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]]:
- **Reduced fronthaul bandwidth**: By moving some Layer 1 functions from [[Def - (RU) Radio Unit|RU]] to [[Def - (DU) Distributed Unit|DU]], it transmits less raw data.
- **Supports statistical multiplexing**: Enables sharing of links across multiple radio channels or sites.
- **Lower latency and better timing**: Still meets the strict timing requirements of [[Def - (RAN) Radio Access Network|RAN]] operation.
- **Interoperability**: Defined by a set of open specifications for multi-vendor environments.

[[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]] enables operators to deploy cloud-native and virtualised radio access networks while preserving performance and reducing transport costs.
