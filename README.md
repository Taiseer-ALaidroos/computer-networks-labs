# 🌐 Large-Scale Network Topology (Cisco Packet Tracer Project)

## 📌 Description
This project implements a **large-scale computer network topology** using Cisco Packet Tracer.

The network simulates a real enterprise/campus environment and includes:
- 3 Routers (Router1, Router2, Router3)
- DNS Server
- 250+ End Devices (Laptops)
- Multiple interconnected network segments

The goal of this project is to demonstrate scalable network design, routing, and DNS-based communication in a simulated environment.

---

## 👨‍💻 Author
**Taiseer Al-Aidrous**  
Artificial Intelligence Student | Networking Enthusiast 🚀  

---

## ⚙️ Features
- 🌐 Multi-router network design (3 routers interconnected)
- 🧭 Inter-network routing between different subnets
- 🖥️ Large-scale end devices (250+ laptops)
- 📡 DNS Server for name resolution
- 🔁 Cross-network communication between all devices
- 📊 Scalable enterprise-style topology design
- 🧪 Simulation of real-world network environments

---

## 🧠 Networking Concepts Used
- IP Addressing & Subnetting  
- Router-to-Router Communication  
- Static / Dynamic Routing (depending on configuration)  
- DNS Configuration & Name Resolution  
- LAN & WAN Design  
- Broadcast domain segmentation  
- Network scalability concepts  

---

## 🏗️ Project Structure

network-topology/
│
├── Large_Network.pkt # Cisco Packet Tracer project file
├── README.md # Project documentation
├── ip-addressing-table.xlsx # IP assignment table (optional)
│
└── configs/
├── router1-config.txt
├── router2-config.txt
├── router3-config.txt
└── dns-server-config.txt


---

## ▶️ How to Run
1. Install **Cisco Packet Tracer (v7.0 or higher)**  
2. Open the file: `Large_Network.pkt`  
3. Wait for the full topology to load (large number of devices)  
4. Test connectivity:
   - Ping between laptops and DNS server  
   - Test communication between different subnets  
   - Verify router-to-router connectivity  

---

## 🔄 Network Workflow
- Routers connect multiple network segments  
- Each router manages a specific subnet of devices  
- Switches distribute connections to laptops  
- DNS Server resolves domain names to IP addresses  
- Data is routed across different networks via routers  

---

## 💡 Key Notes
- This is a **simulated network using Cisco Packet Tracer**
- Focus is on **scalability and routing design**
- No physical hardware required
- Designed for educational networking purposes

---

## 🚀 Future Improvements
- 🔐 Add ACLs (Access Control Lists) for security  
- 🌐 Implement VLAN segmentation  
- 📡 Configure DHCP for automatic IP assignment  
- 🧭 Use dynamic routing protocols (OSPF / EIGRP)  
- 🔥 Add firewall simulation for enterprise security  

---

## ⭐ License
This project is for educational purposes only.
