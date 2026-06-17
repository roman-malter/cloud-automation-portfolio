# Cisco Packet Tracer Infrastructure Library

Welcome to my networking portfolio. This directory showcases a library of 6 production-grade network simulations built within Cisco Packet Tracer. 

These labs validate my practical understanding of high-availability gateway routing, loop-free switching, link aggregation, secure remote access, and advanced infrastructure troubleshooting—the core components needed to design stable Microsoft Azure environments.

---

## 📁 The 6-Project Topology Portfolio

### 1. Lab 3.1.1.5: Examining a Redundant Design
![Cisco Redundancy Topology](./cisco_topology1.png)
* **Core Concepts:** First-Hop Redundancy baselines, Spanning Tree Protocol (STP) convergence, and backup default gateway tracking.
* **The Cloud Pivot:** Mirrors high-availability designs used to orchestrate load-balanced, multi-zone availability structures inside Azure.

### 2. Lab 3.3.1.5: Configuring PVST+ (Per-VLAN Spanning Tree)
![Cisco PVST Topology](./cisco_pvst.png)
* **Core Concepts:** Root bridge election customization, load balancing traffic across independent VLAN paths, and eliminating Layer 2 network loops.
* **The Cloud Pivot:** Aligns directly with segmenting enterprise multi-tenant traffic securely across complex virtualization layers.

### 3. Lab 4.2.1.3: Configuring EtherChannel (Link Aggregation)
![Cisco EtherChannel Topology](./cisco_etherchannel.png)
* **Core Concepts:** PAgP/LACP configurations, combining multiple physical links into one logical high-throughput connection, and interface bandwidth scaling.
* **The Cloud Pivot:** Translates directly to network bandwidth pooling concepts like Azure Virtual Network Peering and high-speed ExpressRoute gateway links.

### 4. Lab 4.3.4.4: Troubleshoot HSRP (Hot Standby Router Protocol)
![Cisco HSRP Troubleshooting](./cisco_topology2.png)
* **Core Concepts:** Active/Standby router priority resolution, tracking timers configuration, and diagnosing virtual MAC address assignment failures.
* **The Cloud Pivot:** Directly mimics cloud incident response workflows, ensuring automated infrastructure failovers operate seamlessly without traffic degradation.

### 5. Lab 5.2.1.4: Configuring SSH (Secure Remote Management)
![Cisco SSH Topology](./cisco_ssh.png)
* **Core Concepts:** Disabling insecure Telnet access, generating RSA cryptographic keys, and enforcing encrypted administrative VTY line access.
* **The Cloud Pivot:** Connects directly with cloud security policies that mandate closing public management ports and enforcing encrypted SSH/Bastion access to cloud VMs.

### 6. Lab 5.2.3.4: Comparing RIP and EIGRP Path Selection
![Cisco Routing Protocol Topology](./cisco_routing.png)
* **Core Concepts:** Administrative Distance comparison metrics, composite routing weights (bandwidth/delay), and dynamic routing table convergence.
* **The Cloud Pivot:** Provides the core routing knowledge required to design custom User Defined Routes (UDRs) and BGP route propagation in Azure networks.
