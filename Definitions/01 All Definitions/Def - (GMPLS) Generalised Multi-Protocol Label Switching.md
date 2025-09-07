---
aliases:
  - Generalised Multi-Protocol Label Switching
  - GMPLS
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---
t
**Generalised Multi-Protocol Label Switching ([[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]])** is an extension of [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] (Multi-Protocol Label Switching) that supports not only packet-switched networks but also other types of switching, such as time, wavelength, and space switching. It is designed to provide a unified control plane for managing diverse network technologies, including optical networks, SONET/SDH, and wavelength-routed systems.

In traditional [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]], labels are used to route packets along predefined paths in a packet-switched network. GMPLS generalises this concept by allowing labels to represent other types of resources, such as:
- **Time slots** in [[Def - (TDM) Time Division Multiplexing|TDM]] networks
- **Wavelengths** in [[Def - (WDM) Wavelength Division Multiplexing|WDM]] optical systems
- **Fibre ports or spatial paths** in optical cross-connects
- **Packet identifiers** in traditional [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] networks

[[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]] includes enhancements in four main areas:
- **Label types**: Supports multiple label types suited to different switching technologies.
- **Routing protocols**: Uses extensions to [[Def - (OSPF) Open Shortest Path First|OSPF]] or [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]] to exchange topology and resource information.
- **Signalling protocols**: Uses [[Def - (RSVP) Resource Reservation Protocol|RSVP]]-TE (Resource Reservation Protocol with Traffic Engineering) for path setup and teardown across different layers.
- **Link management**: Provides mechanisms to manage diverse physical interfaces and their capabilities.

Benefits of [[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]]:
- **Unified control**: Manages mixed-technology networks under a common signalling and routing framework.
- **Automation**: Enables dynamic provisioning and restoration of services without manual configuration.
- **Scalability**: Supports large-scale, multi-layer, and multi-domain networks.
- **Efficiency**: Optimises use of network resources across layers and switching types.

[[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]] plays a key role in enabling intelligent optical networks, including [[Def - (ASON) Automatically Switched Optical Network|ASON]] and next-generation transport systems, by providing the signalling and control mechanisms needed for flexible, end-to-end path management.
