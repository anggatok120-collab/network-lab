# ⚡ Network Lab & Topology Simulator — Angga

Interactive web-based **Enterprise Network Topology & Packet Tracer Simulator** by **Angga** (Network Engineer & NOC Specialist).

---

## 🌟 Features

- 🗺️ **Interactive Enterprise Topology (SVG)**:
  - 💻 **Host-01**: Workstation Client (`192.168.10.101` / VLAN 10)
  - 🔀 **Ruijie Switch**: Access & Trunk Switch (`RG-NBS3100` / VLAN 10/20)
  - 🖥️ **NOC Zabbix Server**: Centralized Monitoring (`192.168.10.50` / SNMP)
  - 🏢 **Huawei Core Switch**: L3 Core Routing (`S5735-L` / `10.0.0.2/30`)
  - 🛡️ **MikroTik Core Router**: Edge BGP Gateway (`CCR2004-1G-12S+` / `10.0.0.1`)
  - 🌐 **Primary WAN**: BGP Gateway (`203.0.113.1`)
  - ☁️ **Backup WAN**: Failover Gateway (`198.51.100.1`)

- 🎮 **Live Simulation Scenarios**:
  1. **ICMP Ping**: End-to-end packet travel with realistic RTT latency calculation ($7.82\text{ ms}$).
  2. **Link Failover**: Simulates BGP/OSPF dynamic route failover to redundant backup WAN when primary link fails.
  3. **VLAN Tagging (802.1Q)**: Visualizes VLAN 10 encapsulation and trunking.
  4. **Firewall Drop Filter**: Simulates illegal port 22 scan blocked by router firewall rules.
  5. **Device Inspector**: Click any device node to inspect IP, OS, VLAN, and interface specifications.

- 🖥️ **Real-Time NOC Route & Packet Console**:
  - Live syntax-highlighted syslog and packet trace logs.

- 🌐 **Bilingual (ID & EN)**:
  - Instant toggle between Bahasa Indonesia and English.

---

## 🚀 Live Demo & Portfolios

- **Network Lab (This Project)**: [anggot.biz.id](https://anggot.biz.id)
- **Main Portfolio**: [anggatok.my.id](https://anggatok.my.id)
- **Terminal Portfolio**: [portfolio.anggatok.my.id](https://portfolio.anggatok.my.id)

---

## 🛠️ Tech Stack

- Vanilla HTML5 / Semantic Layout
- Modern Responsive Vanilla CSS3 (Cyber NOC Dark Theme)
- Vanilla JavaScript (Zero Dependencies, Ultra Fast, 60fps SVG requestAnimationFrame animations)

---

© 2026 Angga. All rights reserved.
