# Cisco-Packet-Tracer-Labs🌐
A collection of my Cisco Packet Tracer lab exercises which i made to practice and demonstrate networking concepts including routing, switching, VLAN configuration, subnetting, and network troubleshooting.


## 📅 Day 1 — Network Topology Setup (Packet Tracer Introduction)

### 🎯 Lab Objective

Create and connect a basic enterprise-style network topology using Cisco devices in **Cisco Packet Tracer**.

This lab focuses on:

* Understanding **network layout**
* Practicing **device selection**
* Building a **foundation for future configurations**

---

### 🧰 Devices Used

The following devices were used to build the topology:

* 🛣️ Cisco 2911 Routers (x2)
* 🔀 Cisco 2960 Switches (x2)
* 🔥 Cisco 5505 Firewalls (x2)
* 💻 PCs (x2)
* 🖥️ Servers (x2)
* 🧑‍💻 Laptop (Attacker machine)

---

### 🗺️ Network Topology

Recreate the network diagram shown in the Day 1 video (timestamp: **16:40**).

> 💡 This topology simulates a **secured network environment** with firewalls and an external attacker.

---

### 🔌 Connections

All devices should be connected using:

> ⚡ **"Automatically Choose Connection Type"** in Cisco Packet Tracer

This ensures:

* Correct cable types are selected automatically
* Faster and easier setup for beginners

---

### 🧪 Lab Tasks

* [ ] Place all required devices in the workspace
* [ ] Connect all devices correctly
* [ ] Ensure proper physical topology layout
* [ ] Label devices (optional but recommended)

---

### 📸 Screenshot



![Day 1 Topology](images/day-1.png)





---
# 📅 Day 2 — Network Cabling & Device Connections

### 🎯 Lab Objective

Connect all devices in the topology using the **correct cable types** while assuming **Auto MDI-X is disabled**.

This lab focuses on:

* Proper **cable selection**
* Understanding **device-to-device connections**
* Building a correct **Layer 1 (Physical Layer)** network

---

### 🧰 Devices Used

* 🛣️ Routers (R1, R2, R3, R4)
* 🔀 Switches (SW1 – SW8)
* 💻 PCs (PC1, PC2, PC3)
* 🖥️ Server (SRV1)

---

### 🗺️ Topology Overview

* R1 connects to R2 and R3
* R3 connects to R4
* Each router connects to switches
* Switches connect to PCs and servers

Distances (important for media choice):

* R1 ↔ R2 → **50 meters**
* R3 ↔ R4 → **250 meters**
* R1 ↔ R3 → **3 kilometers**

---

### 🔌 Cable Selection Rules (Auto MDI-X Disabled)

| Connection         | Cable Type        |
| ------------------ | ----------------- |
| Router ↔ Router    | Crossover / Fiber |
| Router ↔ Switch    | Straight-through  |
| Switch ↔ Switch    | Crossover         |
| Switch ↔ PC/Server | Straight-through  |

---

### 🧠 Fiber Decision (Based on Distance)

| Link    | Distance | Recommended Cable   |
| ------- | -------- | ------------------- |
| R1 ↔ R2 | 50m      | Copper (Crossover)  |
| R3 ↔ R4 | 250m     | Fiber (Multimode)   |
| R1 ↔ R3 | 3km      | Fiber (Single-mode) |

> ⚠️ Packet Tracer does not differentiate between fiber types, but in real networks:

* **Multimode fiber** → short distance (LAN)
* **Single-mode fiber** → long distance (WAN)

---

### 🧪 Lab Tasks

* [ ] Connect all routers correctly
* [ ] Connect switches to routers
* [ ] Connect end devices (PCs, Server)
* [ ] Use correct cable types (no auto mode)
* [ ] Ensure all links are **green (active)**

---

### 📸 Topology Screenshot

![Day 2 Topology](images/day-2.png)


---


