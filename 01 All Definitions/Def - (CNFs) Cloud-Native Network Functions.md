---
aliases:
  - Cloud-Native Network Functions
  - CNFs
tags:
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/standardisation-and-organisations
---

**Cloud-Native Network Functions (CNFs)** are **containerised implementations** of traditional network functions that are designed to run on **cloud-native infrastructure**, such as **Kubernetes**. CNFs represent the next evolution in virtualisation beyond Virtual Network Functions (VNFs), aligning with principles of **microservices, scalability, automation, and resiliency**.

While **VNFs** run on virtual machines (VMs) and are managed using NFV MANO frameworks, **CNFs** are built to run in **containers**, making them lightweight, modular, and portable. They are deployed using **cloud-native tools** and orchestrated by platforms such as **Kubernetes**, often integrated with **service meshes**, **DevOps pipelines**, and **CI/CD automation**.

Key characteristics of CNFs:
- **Microservices-based architecture**: Functions are decomposed into smaller components that can be independently deployed, scaled, and updated.
- **Containerised deployment**: Uses Docker or OCI-compliant containers, improving resource utilisation and agility.
- **Orchestrated with Kubernetes**: CNFs are scheduled, managed, and monitored using Kubernetes-native mechanisms (e.g. Helm, Operators).
- **Stateless and stateful workloads**: Supports design patterns for horizontal scaling and persistent network state.
- **Cloud-native integrations**: Tied closely to observability, auto-healing, logging, and configuration management tools.

Benefits of CNFs:
- **Faster deployment and updates**: Enables rolling updates, zero-downtime deployments, and easier testing.
- **High scalability**: Functions can scale independently based on demand and resource availability.
- **Platform agnosticism**: Run on public, private, or hybrid cloud environments.
- **Reduced overhead**: Lightweight containers require less compute and storage than VMs.

Use cases:
- **5G Core (5GC)** network functions (e.g. AMF, SMF, UPF)
- **Security functions** (e.g. firewalls, IDS)
- **Edge computing**: Low-latency CNFs deployed at the network edge
- **Service meshes**: Managing service-to-service communication between CNFs

As telecommunications shifts toward **5G, O-RAN**, and **edge-native** deployments, CNFs are becoming the standard for building and operating modern, agile, and programmable networks.
