from pathlib import Path
import shutil

src = Path("/mnt/data/Screenshot 2026-09-22 230026.png")
topology = Path("/mnt/data/practical-02-topology.png")
shutil.copy2(src, topology)

readme = """# 🌐 Cisco Packet Tracer – Practical 02

<p align="center">
  <img src="practical-02-topology.png" alt="Cisco Packet Tracer Practical 02 Topology" width="800">
</p>

## 📌 Practical Overview

This is my **2nd Cisco Packet Tracer practical**.

In this practical, a basic LAN topology is created using **two Cisco 2960-24TT switches and five PCs**. The PCs are connected to the switches, and the two switches are connected to each other to form a small network.

## 🎯 Objectives

- Create a basic network topology using Cisco Packet Tracer.
- Connect multiple PCs to a Cisco switch.
- Connect two switches together.
- Understand basic LAN connectivity.
- Practice physical network topology design.
- Observe the status of network connections.

## 🖥️ Network Devices

| Device | Quantity |
|---|---:|
| PC-PT | 5 |
| Cisco 2960-24TT Switch | 2 |

## 🔗 Network Topology

The topology contains:

- **PC1, PC2, PC3 and PC0** connected to **Switch0**
- **Switch0** connected to **Switch1**
- **PC4** connected to **Switch1**

### Topology Diagram

<p align="center">
  <img src="practical-02-topology.png" alt="Practical 02 Network Topology" width="800">
</p>

## 🧩 Concepts Practiced

- LAN (Local Area Network)
- Ethernet Networking
- Cisco Switches
- End Device Connectivity
- Switch-to-Switch Connectivity
- Basic Network Topology

## 🛠️ Software Used

- **Cisco Packet Tracer**

## 📁 Files

- `Practical-02.pkt` – Cisco Packet Tracer practical file
- `practical-02-topology.png` – Network topology screenshot
- `README.md` – Practical documentation

## 🧪 Testing

Network connectivity can be tested using the **Ping** command after assigning appropriate IP addresses to the PCs.

Example:

```bash
ping <destination-IP-address>
