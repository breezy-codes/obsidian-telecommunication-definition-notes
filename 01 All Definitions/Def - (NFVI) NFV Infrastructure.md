---
aliases:
  - NFV Infrastructure
  - NFVI
tags:
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/standardisation-and-organisations
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/cross-layer
---

**NFV Infrastructure ([[Def - (NFVI) NFV Infrastructure|NFVI]])** refers to the **virtualised hardware and software environment** in which **Virtual Network Functions ([[Def - (VNFs) Virtual Network Functions|VNF]]s)** are deployed, managed, and executed. It forms the **foundation layer** of the [[Def - (ETSI) European Telecommunications Standards Institute|ETSI]] [[Def - (NFV) Network Functions Virtualisation|NFV]] architecture and includes the **compute, storage, and networking resources** required to support network virtualisation.

[[Def - (NFVI) NFV Infrastructure|NFVI]] abstracts physical infrastructure resources so they can be shared, allocated, and scaled dynamically across multiple [[Def - (VNFs) Virtual Network Functions|VNF]]s and services. This enables network operators to replace dedicated, proprietary network appliances with **general-purpose hardware** and cloud-like virtualisation technologies.

Core components of [[Def - (NFVI) NFV Infrastructure|NFVI]]:
- **Compute resources**: General-purpose CPUs (often x86) with virtualisation support (e.g. KVM, VMware ESXi).
- **Storage resources**: Block, file, or object storage used by [[Def - (VNFs) Virtual Network Functions|VNF]]s, either local or via virtual storage systems.
- **Networking resources**: Virtual and physical switches, NICs, [[Def - (SDN) Software Defined Networking|SDN]] components, and virtual routers providing data connectivity between [[Def - (VNFs) Virtual Network Functions|VNF]]s and external networks.

Virtualisation layer:
- Provides abstraction via **hypervisors** (e.g. KVM, VMware), or **container runtimes** (e.g. Docker) in cloud-native environments.
- Supports **resource pooling** and **isolation** between [[Def - (VNFs) Virtual Network Functions|VNF]]s.

Key features of [[Def - (NFVI) NFV Infrastructure|NFVI]]:
- **Multi-tenancy**: Supports multiple services and tenants on shared infrastructure.
- **Elastic resource management**: Enables dynamic allocation and scaling based on demand.
- **Hardware independence**: Decouples network functions from underlying proprietary appliances.
- **Programmability and automation**: Facilitates integration with orchestration and DevOps tools for lifecycle management.

[[Def - (NFVI) NFV Infrastructure|NFVI]] is managed by the **Virtualised Infrastructure Manager (VIM)**, which coordinates resource provisioning, monitoring, and fault management.

[[Def - (NFVI) NFV Infrastructure|NFVI]] enables key [[Def - (NFV) Network Functions Virtualisation|NFV]] goals such as:
- **Reduced CAPEX/OPEX** by leveraging commodity hardware.
- **Faster time-to-market** for new services.
- **Flexible deployment models**, including centralised data centres, distributed edge sites, and hybrid cloud environments.

As networks transition to **cloud-native and 5G**, NFVI is evolving to support **containers**, **hardware acceleration** (e.g. DPDK, SR-IOV, SmartNICs), and **edge computing** requirements.
