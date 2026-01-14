# Automated Vxlan Spine-Leaf Fabric Provisioning With Dynamic Ip/Vni Management And Cloud-Based Monitoring
This repository houses the automation engine for an Event-Driven VXLAN-EVPN Spine-Leaf Fabric, designed for scalable and observable data center operations. This project replaces traditional manual configuration with a modern Infrastructure-as-Code (IaC) approach, utilizing a centralized Source of Truth (SoT) to drive network state.
+3

---
## 🚀 Key Project Objectives
- Zero-Touch Provisioning (ZTP) Logic: Automates the complete lifecycle of a 2x2 Cisco Nexus 9300 fabric, including OSPF underlay and BGP EVPN overlay.
- Event-Driven Workflows: Utilizes NetBox Webhooks to trigger Semaphore/Ansible pipelines, ensuring the physical network stays synchronized with the SoT in real-time.
- Dynamic Inventory Management: Eliminates static variable files by dynamically querying NetBox for IP allocations and VNI/VLAN mappings.
- Integrated Observability: Provides deep network visibility through the PLG Stack (Prometheus, Loki, Grafana) to monitor fabric health and telemetry.

## 🛠️ Technical Stack
- Network Emulation: Containerlab (running Cisco NX-OSv).
- Source of Truth: NetBox (IPAM/VNI Management).
- Automation Engine: Ansible & Semaphore UI.
- Observability: Prometheus (Metrics), Loki (Logs), Grafana (Visualization), Alloy, Rsyslog
