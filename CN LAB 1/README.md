# 🌐 Network Topologies Simulation using Cisco Packet Tracer

## 📌 Overview

This project demonstrates the design and simulation of four fundamental network topologies using Cisco Packet Tracer:

* Star Topology
* Bus Topology
* Ring Topology
* Mesh Topology

The goal is to understand how data flows in different network structures and compare their efficiency, reliability, and performance.

---

## 🛠️ Tools Used

* Cisco Packet Tracer
* GitHub for documentation

---

## 🧩 Topologies Implemented

### ⭐ Star Topology

* Central device: Switch
* All PCs connected to the switch

📷 Screenshot:
![Star Topology](images/star.png)

---

### 🚌 Bus Topology

* All devices connected through a single hub

📷 Screenshot:
![Bus Topology](images/bus.png)

---

### 🔁 Ring Topology

* Devices connected in a circular loop

📷 Screenshot:
![Ring Topology](images/ring.png)

---

### 🕸️ Mesh Topology

* Every device connected to every other device

📷 Screenshot:
![Mesh Topology](images/mesh.png)

---

## 🌐 IP Configuration

| Topology | IP Range    |
| -------- | ----------- |
| Star     | 192.168.1.x |
| Bus      | 192.168.2.x |
| Ring     | 192.168.3.x |
| Mesh     | 192.168.4.x |

Subnet Mask: 255.255.255.0

---

## 🧪 Testing & Simulation

### ✔ Ping Testing

Used Command Prompt in each PC:
ping <destination IP>

Result:

* All devices successfully communicated

### ✔ Simulation Mode

* Used Packet Tracer Simulation Mode
* Observed packet flow using PDU
* All packets successfully reached destination

---

## 📊 Comparison of Topologies

| Topology | Advantages      | Disadvantages                        |
| -------- | --------------- | ------------------------------------ |
| Star     | Easy to manage  | Switch failure affects all           |
| Bus      | Low cost        | Entire network fails if cable breaks |
| Ring     | Organized flow  | Single break disrupts network        |
| Mesh     | Highly reliable | Expensive and complex                |

---

## 📸 Screenshots

Screenshots of each topology and simulation results are included in the `images/` folder.

---

## 📂 Project Structure

Network-Topologies-Simulation/
│── star.pkt
│── bus.pkt
│── ring.pkt
│── mesh.pkt
│── images/
│   ├── star.png
│   ├── bus.png
│   ├── ring.png
│   ├── mesh.png
│── README.md

---

## 🚀 How to Run

1. Open Cisco Packet Tracer
2. Load any `.pkt` file
3. Assign IP (if needed)
4. Use ping command to test
5. Switch to Simulation Mode to visualize packets

---

## 🎯 Conclusion

* Star topology is simple and widely used
* Mesh provides maximum reliability
* Bus and Ring have limitations in scalability and fault tolerance

---

## 👨‍💻 Author
Golla Diwakar yadav
2401361032
Btech CSE UIUX
