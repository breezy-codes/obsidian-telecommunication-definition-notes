---
aliases:
  - VNF Manager
  - VNFM
tags:
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/cross-layer
---

**VNF Manager ([[Def - (VNFM) VNF Manager|VNFM]])** is a key component of the **[[Def - (NFV) Network Functions Virtualisation|NFV]] [[Def - (MANO) Management and Orchestration|MANO]] (Management and Orchestration)** framework defined by [[Def - (ETSI) European Telecommunications Standards Institute|ETSI]]. The [[Def - (VNFM) VNF Manager|VNFM]] is responsible for the **lifecycle management of Virtual Network Functions ([[Def - (VNFs) Virtual Network Functions|VNF]]s)**, which are software implementations of traditional network functions (e.g. firewalls, routers, EPC components) running on virtualised infrastructure.

Core responsibilities of the [[Def - (VNFM) VNF Manager|VNFM]]:
- **Lifecycle operations**: Handles [[Def - (VNFs) Virtual Network Functions|VNF]] instantiation, scaling, healing (recovery), updating, and termination.
- **Element management**: Interfaces with Element Managers (EMs) and [[Def - (VNFs) Virtual Network Functions|VNF]]s for configuration and fault management.
- **Monitoring and automation**: Collects performance and fault data to trigger automatic responses or notify the [[Def - (NFVO) NFV Orchestrator|NFVO]].
- **State synchronisation**: Ensures the [[Def - (VNFs) Virtual Network Functions|VNF]]'s internal state is consistent with the management systems.

Types of [[Def - (VNFM) VNF Manager|VNFM]]:
- **Generic VNFM**: Supports a wide variety of [[Def - (VNFs) Virtual Network Functions|VNF]]s from different vendors using standard descriptors (e.g. TOSCA or ETSI VNFD).
- **Specific VNFM**: Designed to manage a particular [[Def - (VNFs) Virtual Network Functions|VNF]] or vendor product, with deep integration and custom operations.

The [[Def - (VNFM) VNF Manager|VNFM]] works in close coordination with:
- The **NFV Orchestrator ([[Def - (NFVO) NFV Orchestrator|NFVO]])**, which provides high-level service orchestration.
- The **VIM**, to request resources for scaling or recovery.
- **EMs and OSS/BSS**, to integrate with broader operational processes.

As networks move toward **cloud-native network functions ([[Def - (CNFs) Cloud-Native Network Functions|CNFs]]s)**, VNFM functions are increasingly implemented using Kubernetes-native approaches (e.g. operators, Helm charts), though traditional [[Def - (VNFs) Virtual Network Functions|VNF]] management remains crucial in hybrid deployments.
