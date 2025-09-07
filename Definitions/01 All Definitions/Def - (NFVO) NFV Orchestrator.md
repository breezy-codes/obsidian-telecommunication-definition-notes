---
aliases:
  - NFV Orchestrator
  - NFVO
tags:
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/standardisation-and-organisations
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/cross-layer
---

**NFV Orchestrator ([[Def - (NFVO) NFV Orchestrator|NFVO]])** is a core component of the **[[Def - (ETSI) European Telecommunications Standards Institute|ETSI]] Network Functions Virtualisation ([[Def - (NFV) Network Functions Virtualisation|NFV]]) Management and Orchestration ([[Def - (MANO) Management and Orchestration|MANO]])** framework. The [[Def - (NFVO) NFV Orchestrator|NFVO]] is responsible for the **orchestration and lifecycle management** of network services (NS) and their associated resources across a **virtualised infrastructure**.

Key responsibilities of the [[Def - (NFVO) NFV Orchestrator|NFVO]]:
- **Network service orchestration**: Manages the deployment, scaling, updating, and termination of end-to-end services composed of multiple Virtual Network Functions ([[Def - (VNFs) Virtual Network Functions|VNF]]s).
- **Resource orchestration**: Coordinates virtualised compute, storage, and networking resources from one or more Virtualised Infrastructure Managers (VIMs) such as OpenStack or VMware.
- **Multi-VIM support**: Can interact with multiple infrastructure domains for hybrid or distributed deployments.
- **Service chaining and placement**: Determines optimal placement of [[Def - (VNFs) Virtual Network Functions|VNF]]s to meet performance, latency, or policy requirements.
- **Policy enforcement and SLA management**: Ensures service-level objectives and business rules are maintained throughout the lifecycle.

The [[Def - (NFVO) NFV Orchestrator|NFVO]] communicates with:
- The **VNF Manager ([[Def - (VNFM) VNF Manager|VNFM]])** for VNF lifecycle operations.
- The **VIM** for virtual resource orchestration.
- **OSS/BSS systems** for integration with higher-level service management and billing platforms.

As 5G networks adopt service-based and cloud-native architectures, the [[Def - (NFVO) NFV Orchestrator|NFVO]] is evolving to support container-based network functions (CNFs) and multi-domain orchestration within platforms like OSM (Open Source [[Def - (MANO) Management and Orchestration|MANO]]) and ONAP.
