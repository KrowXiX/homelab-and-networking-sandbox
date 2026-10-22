# homelab-and-networking-sandbox
A hands-on enterprise homelab showcasing Linux/Windows virtualization, Python automation, complex Layer 3 traffic routing (WireGuard split tunnels), and Dynamic DNS/port-forwarding pipeline architecture.

# Comprehensive Enterprise-Grade Homelab & Systems Sandbox

Welcome to my portfolio! This repository documents the architecture, automation, traffic engineering, and infrastructure deployments I manage within my private homelab. This environment serves as my hands-on testing ground for mastering systems administration and network security fundamentals.

---

## 🛠️ Core Infrastructure & Virtualization
*   **Operating Systems:** Hybrid deployment across Windows 11 host machines and standalone Linux Virtual Machines (VMs).
*   **Virtualization:** Configured hypervisor environments to isolate server instances, test deployment protocols, and study OS fundamentals.
*   **Application Servers:** Deployed automated game server instances and a dedicated Plex media distribution architecture.

## 🎛️ Automation, Scripting & Orchestration
*   **Scripting:** Engineered custom Python and Windows Batch (.bat) scripts to handle backend server processes, log aggregation, and system maintenance.
*   **Task Scheduling:** Deployed system-level automation routines utilizing Task Manager (Windows) and Cron utilities (Linux) to manage cron jobs and automated file updates.

## 🌐 Advanced Traffic Engineering & Network Security
*   **Layer 2 Deployment:** Integrated a physical managed network switch to aggregate high-bandwidth multimedia and gaming infrastructure, separating localized data frames from wireless environments.
*   **Layer 3 Encryption Protocol:** Implemented a system-wide desktop encryption tunnel utilizing Private Internet Access (PIA) running natively on the high-throughput, multithreaded WireGuard protocol.
*   **Dynamic DNS & Edge Routing:** Formulated a complex, multi-layered remote access loop:
    *   Masked local infrastructure traffic securely within the VPN tunnel.
    *   Integrated **No-IP (Dynamic DNS)** client tracking to seamlessly monitor fluctuating public IP handshakes.
    *   Bound dynamic hostname records securely back to a private, custom-owned **DNS server**.
*   **Port Forwarding & Protocol Rules:** Engineered strict ingress port forwarding rules at the primary router firewall boundary, safely translating external network requests directly down to internal application endpoints.

---

## 🛡️ Career Alignment (SOC Analyst Track)
This production sandbox directly mirrors enterprise network environments. Managing this deployment has given me deep practical competency in:
*   Analyzing OSI Layer 2/3 traffic and frame delivery.
*   Configuring and auditing router firewall boundaries (Port Forwarding/ACLs).
*   Troubleshooting DNS mapping, query resolution, and network latency bottlenecks.
*   Navigating the Linux command line environment and managing task persistence.
