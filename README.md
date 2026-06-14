<div align="center">

# 🌐 Network Labs — Layer 2 & Layer 3 Deep Dive

**Practical Cisco networking lab configurations, topologies & troubleshooting guides**  
Built on GNS3 / EVE-NG · Cisco IOS XE · CCNP / CCIE Level

[![Labs](https://img.shields.io/badge/Labs-In%20Progress-yellow?style=flat-square&logo=cisco)](https://github.com/daviddu1906/network-labs)
[![Level](https://img.shields.io/badge/Level-CCNP%20%7C%20CCIE-blue?style=flat-square)](https://github.com/daviddu1906/network-labs)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](./LICENSE)
[![Author](https://img.shields.io/badge/Author-David%20Du-orange?style=flat-square&logo=linkedin)](https://linkedin.com/in/YOUR_PROFILE)

</div>

---

## 👤 About This Repository

This repository documents my hands-on journey building and troubleshooting **Layer 2 and Layer 3 network labs** using Cisco IOS XE on GNS3 / EVE-NG.

Each lab includes:
- 📐 **Topology diagram** — visual network design
- ⚙️ **Device configurations** — sanitized, production-style configs
- 📖 **Concept notes** — theory behind each feature
- 🔧 **Troubleshooting case studies** — real-world failure scenarios and fixes

> **Goal:** Build a comprehensive reference library covering every major L2/L3 technology at CCNP/CCIE depth.

---

## 🗺️ Lab Roadmap

### 🔵 LAYER 2 — Switching & Data Link Technologies

| # | Technology | Lab Folder | Key Topics | Status |
|---|-----------|-----------|------------|--------|
| 01 | **VLAN** | `L2/VLAN/` | 802.1Q tagging, Access/Trunk port, Native VLAN, Extended VLAN | ✅ Done |
| 02 | **Private VLAN (PVLAN)** | `L2/PVLAN/` | Isolated, Community, Promiscuous port, PCI-DSS use case | ✅ Done |
| 03 | **VTP** | `L2/VTP/` | VTP v1/v2/v3, Server/Client/Transparent/Off, Revision attack | 🔜 Planned |
| 04 | **DTP** | `L2/DTP/` | Dynamic trunk negotiation, desirable/auto/nonegotiate | 🔜 Planned |
| 05 | **Trunking** | `L2/Trunking/` | 802.1Q, ISL (legacy), trunk allowed VLAN list | 🔜 Planned |
| 06 | **STP** | `L2/STP/` | 802.1D, PVST+, Rapid PVST+, MSTP (802.1s), port states | 🔜 Planned |
| 07 | **STP Security** | `L2/STP-Security/` | PortFast, BPDU Guard, BPDU Filter, Root Guard, Loop Guard | 🔜 Planned |
| 08 | **EtherChannel** | `L2/EtherChannel/` | PAgP, LACP (802.3ad), Static, load-balancing hash | 🔜 Planned |
| 09 | **Port Security** | `L2/Port-Security/` | MAC limit, sticky MAC, violation modes (shutdown/restrict/protect) | 🔜 Planned |
| 10 | **DHCP Snooping** | `L2/DHCP-Snooping/` | Trusted/untrusted port, binding table, rate limiting | 🔜 Planned |
| 11 | **Dynamic ARP Inspection (DAI)** | `L2/DAI/` | ARP spoofing prevention, per-VLAN, ARP ACL for static hosts | 🔜 Planned |
| 12 | **IP Source Guard (IPSG)** | `L2/IPSG/` | Binding table enforcement, static binding | 🔜 Planned |
| 13 | **Storm Control** | `L2/Storm-Control/` | Broadcast/multicast/unicast storm, rising/falling threshold | 🔜 Planned |
| 14 | **CDP / LLDP** | `L2/CDP-LLDP/` | Neighbor discovery, security implications, disable per-port | 🔜 Planned |
| 15 | **802.1X (NAC)** | `L2/8021X/` | Port-based auth, EAP methods, MAB fallback, ISE integration | 🔜 Planned |
| 16 | **MACsec (802.1AE)** | `L2/MACsec/` | L2 encryption, CAK/CKN, MKA protocol | 🔜 Planned |
| 17 | **QinQ (802.1ad)** | `L2/QinQ/` | Double tagging, S-TAG/C-TAG, SP tunneling | 🔜 Planned |
| 18 | **Flex Links** | `L2/Flex-Links/` | L2 redundancy without STP | 🔜 Planned |
| 19 | **UDLD** | `L2/UDLD/` | Unidirectional link detection, normal/aggressive mode | 🔜 Planned |
| 20 | **Spanning Tree Optimization** | `L2/STP-Tuning/` | Timer tuning, load balancing per VLAN, UplinkFast, BackboneFast | 🔜 Planned |

---

### 🟠 LAYER 3 — Routing & Network Technologies

| # | Technology | Lab Folder | Key Topics | Status |
|---|-----------|-----------|------------|--------|
| 21 | **Inter-VLAN Routing** | `L3/Inter-VLAN/` | Router-on-a-Stick, SVI, L3 Switch routed port | 🔜 Planned |
| 22 | **Static Routing** | `L3/Static-Routing/` | Static, default, floating static, recursive lookup | 🔜 Planned |
| 23 | **OSPF** | `L3/OSPF/` | OSPFv2, area types, DR/BDR, LSA types, route summarization | 🔜 Planned |
| 24 | **OSPFv3** | `L3/OSPFv3/` | IPv6 support, address families, dual-stack | 🔜 Planned |
| 25 | **EIGRP** | `L3/EIGRP/` | DUAL algorithm, feasible successor, stub, named mode | 🔜 Planned |
| 26 | **BGP** | `L3/BGP/` | eBGP, iBGP, attributes, path selection, route reflector | 🔜 Planned |
| 27 | **BGP Advanced** | `L3/BGP-Advanced/` | Communities, policy, prefix filtering, AS-path manipulation | 🔜 Planned |
| 28 | **Route Redistribution** | `L3/Redistribution/` | Multi-protocol redistribution, metric, tag, prevent loops | 🔜 Planned |
| 29 | **Policy-Based Routing (PBR)** | `L3/PBR/` | route-map, set ip next-hop, traffic steering | 🔜 Planned |
| 30 | **VRF / VRF-Lite** | `L3/VRF/` | VRF definition, route leaking, multi-tenant routing | 🔜 Planned |
| 31 | **HSRP** | `L3/HSRP/` | HSRPv1/v2, preemption, tracking, active/standby | 🔜 Planned |
| 32 | **VRRP** | `L3/VRRP/` | VRRPv2/v3, master election, IPv6 support | 🔜 Planned |
| 33 | **GLBP** | `L3/GLBP/` | Load balancing FHR, AVG/AVF roles | 🔜 Planned |
| 34 | **DHCP Server / Relay** | `L3/DHCP/` | DHCP pool, ip helper-address, option 82, DHCP failover | 🔜 Planned |
| 35 | **NAT / PAT** | `L3/NAT/` | Static NAT, Dynamic NAT, PAT (overload), NAT troubleshooting | 🔜 Planned |
| 36 | **IPv6 Addressing** | `L3/IPv6/` | GUA, LLA, EUI-64, SLAAC, DHCPv6 stateful/stateless | 🔜 Planned |
| 37 | **IPv6 Routing** | `L3/IPv6-Routing/` | OSPFv3, EIGRPv6, BGP IPv6 AF, static IPv6 | 🔜 Planned |
| 38 | **IP SLA** | `L3/IP-SLA/` | ICMP echo, UDP jitter, track object, floating static trigger | 🔜 Planned |
| 39 | **Prefix Lists & Route Maps** | `L3/Prefix-Route-Map/` | ip prefix-list, route-map match/set, policy chaining | 🔜 Planned |
| 40 | **QoS (L3 Perspective)** | `L3/QoS/` | DSCP marking, queuing, shaping, policing, MQC framework | 🔜 Planned |

---

### 🟣 OVERLAY & ADVANCED (Bonus Labs)

| # | Technology | Lab Folder | Key Topics | Status |
|---|-----------|-----------|------------|--------|
| 41 | **GRE Tunnel** | `Advanced/GRE/` | Point-to-point tunnel, GRE over IPsec | 🔜 Planned |
| 42 | **IPsec VPN** | `Advanced/IPsec/` | IKEv1/v2, transform set, crypto map, tunnel/transport mode | 🔜 Planned |
| 43 | **DMVPN** | `Advanced/DMVPN/` | Hub-and-Spoke, NHRP, Phase 1/2/3 | 🔜 Planned |
| 44 | **MPLS** | `Advanced/MPLS/` | Label switching, LDP, MPLS L3VPN, PE-CE routing | 🔜 Planned |
| 45 | **VXLAN** | `Advanced/VXLAN/` | VNI, VTEP, BUM traffic, EVPN control plane | 🔜 Planned |
| 46 | **SD-WAN Concepts** | `Advanced/SDWAN/` | Overlay, underlay, vSmart policy, ZTP | 🔜 Planned |

---

## 📁 Repository Structure

```
network-labs/
│
├── L2/                          # Layer 2 Labs
│   ├── VLAN/
│   │   ├── configs/             # Device configurations
│   │   ├── topology/            # Diagram (PNG + draw.io source)
│   │   ├── docs/                # Notes & troubleshooting
│   │   └── README.md
│   ├── PVLAN/
│   ├── VTP/
│   ├── STP/
│   └── .../
│
├── L3/                          # Layer 3 Labs
│   ├── Inter-VLAN/
│   ├── OSPF/
│   ├── BGP/
│   └── .../
│
├── Advanced/                    # Overlay & Advanced Labs
│   ├── VXLAN/
│   ├── MPLS/
│   └── .../
│
└── README.md                    # This file
```

---

## 🛠️ Lab Environment

| Component | Details |
|-----------|---------|
| **Simulator** | GNS3 / EVE-NG |
| **Platform** | Cisco IOS XE 17.x |
| **Devices** | Cisco Catalyst 9000v, CSR1000v, IOSvL2 |
| **Host OS** | macOS (Apple Silicon) |
| **Tools** | draw.io (topology), VS Code (config editing) |

---

## 📐 How to Use This Repository

```bash
# 1. Clone the repository
git clone https://github.com/daviddu1906/network-labs

# 2. Navigate to the lab you want
cd network-labs/L2/PVLAN

# 3. Read the lab README
cat README.md

# 4. Import topology into GNS3 or EVE-NG
#    → Open topology/pvlan-topology.png for reference

# 5. Apply configs to devices
#    → configs/SW1-config.txt → paste into device terminal
```

---

## ⚠️ Configuration Disclaimer

All configurations in this repository have been **sanitized**:
- Passwords replaced with `<REDACTED>`
- Production IP addresses replaced with RFC 5737 documentation ranges (`192.0.2.x`, `198.51.100.x`)
- SNMP community strings removed

Configurations are intended for **lab and educational purposes only**.

---

## 📬 Connect

| Platform | Link |
|----------|------|
| 💼 LinkedIn | [linkedin.com/in/YOUR_PROFILE](https://linkedin.com/in/YOUR_PROFILE) |
| 🐙 GitHub | [github.com/daviddu1906](https://github.com/daviddu1906) |
| 📧 Email | duphuoctanct@gmail.com |

---

<div align="center">

**If this repository helped you, consider giving it a ⭐**  
*Built with passion for networking — one lab at a time.*

</div>
