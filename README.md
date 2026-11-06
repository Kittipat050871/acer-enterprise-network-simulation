# Acer Services Center - Enterprise Network Simulation

**Academic team project | Network Administration | Cisco Packet Tracer**

> This is a **fictional university exercise** using an Acer service-center scenario. It is not an Acer corporate network or an official Acer deployment.

## Overview

Our team designed a simulated enterprise network covering a headquarters and two regional branch sites. The academic project explored segmentation between departments, campus/branch routing, switching, and WAN interconnection. The original project report labels sites **BKK, CBI, and NMA** (Bangkok, Chonburi, and Nakhon Ratchasima). One early paragraph in the report mentions a different city; site names here follow the topology labels.

## Network technologies documented

- **VLANs** for departmental separation, including management, customer service, accounting, technical support, quality control and central services
- **VTP** server/client configuration for VLAN management in the simulated topology
- **Layer-3 switching / inter-VLAN connectivity** and IP addressing plans
- **RIP** router configurations and **Frame Relay** WAN simulation
- **Server/services configuration** including DNS, email and web services (as described in the source report)

## Repository contents

```text
README.md
packet-tracer/G12_Project1101183.pkt
  # Original Cisco Packet Tracer file

docs/Acer_Network_Case_Study.pdf
  # Short, privacy-conscious portfolio case study
```

## Inspect the simulation

1. Install a compatible version of **Cisco Packet Tracer**.
2. Download and open [`packet-tracer/G12_Project1101183.pkt`](packet-tracer/G12_Project1101183.pkt).
3. Inspect branch routers, department VLANs, switch modes, and WAN links.
4. Rerun device checks and end-to-end tests independently. **The portfolio repackaging has not rerun Packet Tracer.**

## Scope, limitations, and attribution

- Original submission: **1101183 - Project in Network Administration**, Suranaree University of Technology.
- **Student team project**; do not interpret this as an individually built production network.
- The project report describes intended settings and topology; results have not been independently revalidated in the current Packet Tracer version.
- No real enterprise infrastructure was accessed or deployed.
- The source report is retained privately; this repository includes a rewritten case study instead of the original PDF containing other students' personal details.

## Before making this repository public

**Review the `.pkt` file in Packet Tracer for embedded exercise passwords, device usernames, Wi-Fi keys and identifying details.** Because the `.pkt` format is opaque, an external string scan alone cannot verify that the file contains no secrets. Confirm team permission for shared project materials before making it public.
