
# 🐾 Animal Kingdom Network Design Project 🌐

A complete computer network design and implementation project using **Cisco Packet Tracer**, based on a fictional *Animal Kingdom* divided into multiple tribes with centralized services and hybrid routing.

---

## 📌 Project Overview

The Animal Kingdom is divided into four tribes:

| Tribe 🐯 | Population |
|----------|------------|
| Lion 🦁 | 3 |
| Cat 🐱 | 800 |
| Dog 🐶 | 1200 |
| Elephant 🐘 | 100 |

The Lion tribe acts as the **central authority** and manages all network services including:

- 🌍 Web Server  
- 📛 DNS Server  
- 📧 Email Server  
- 📡 DHCP Server  

The network is designed using **VLSM subnetting**, **static & dynamic routing**, and supports **inter-tribe communication**.

---

## 🎯 Objectives

- Design a scalable network using **VLSM**
- Implement hybrid routing (Static + Dynamic)
- Configure centralized servers
- Enable communication between all tribes
- Host a website: `www.animals.com`
- Enable email between tribal chiefs
- Demonstrate real-world enterprise networking concepts

---

## 🏗️ Network Architecture

### 🔌 Topology Highlights

- Lion tribe directly connected to Elephant tribe
- Elephant tribe connects to Cat & Dog tribes
- All services hosted in Lion tribe
- Chiefs use static IP addressing
- Other devices use DHCP

---

## 🧮 IP Addressing Strategy

- Base Network: `192.168.0.0/16` (example)
- Subnetting using **VLSM**

| Tribe | Subnet | Mask | Hosts |
|-------|--------|-------|--------|
| Dog | /21 | 255.255.248.0 | 2046 |
| Cat | /22 | 255.255.252.0 | 1022 |
| Elephant | /25 | 255.255.255.128 | 126 |
| Lion | /29 | 255.255.255.248 | 6 |

---

## 🧭 Routing Protocols Used

| Tribe | Routing Type |
|-------|--------------|
| Lion | Static Routing |
| Elephant | Dynamic Routing |
| Cat | Dynamic Routing |
| Dog | Dynamic Routing |

Dynamic routing protocol: **RIP v2 / OSPF** (based on implementation)

---

## 🖥️ Services Configured

### 🌐 Web Server
- URL: `www.animals.com`
- Content: *Welcome to the Animal Kingdom!*

### 📛 DNS Server
- Resolves domain names
- Supports website & email domain

### 📧 Email Server
| Chief | Email |
|-------|--------|
| Lion | lionking@animals.com |
| Cat | catchief@animals.com |
| Dog | dogchief@animals.com |
| Elephant | elephantchief@animals.com |

### 📡 DHCP Server
- Assigns IPs to all non-chief devices

---

## 🧪 Testing & Validation

The following tests were successfully performed:

- ✅ Ping between all tribes
- ✅ DNS resolution
- ✅ Website accessibility
- ✅ Email sending & receiving
- ✅ DHCP address allocation
- ✅ Inter-router connectivity

---

## 📁 Repository Contents

📦 Animal-Kingdom-Network

- 📄 README.md
- 📄 AnimalKingdom.pkt
- 📄 Network_Topology.png

---

## 📚 Concepts Applied

- VLSM subnetting
- Static & Dynamic routing
- DHCP relay
- DNS resolution
- Client-server architecture
- Hierarchical network design
- Enterprise network planning

---

## 🚀 How to Run the Project

1. Install **Cisco Packet Tracer**
2. Open the `.pkt` file
3. Switch to Simulation Mode (optional)
4. Test connectivity using ping, browser, and email

---

## ⭐ If you like this project...

Give it a star ⭐ and feel free to fork or improve it!

Happy Networking! 🧠🌐

