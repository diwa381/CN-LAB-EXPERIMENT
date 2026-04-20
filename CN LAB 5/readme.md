# 🌐 Flow Control and Error Control Protocols Simulation

## 📌 Objective

To design and simulate flow control and error control protocols including Stop and Wait, Go-Back-N ARQ, and Selective Repeat ARQ using Cisco Packet Tracer, and compare their performance in terms of throughput and efficiency.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs (Sender and Receiver)
* 1 Router (optional for multi-network simulation)
* 1 Switch

### Topology Design:

PC0 → Switch → Router → Switch → PC1

---

## 🌐 IP Configuration

### PC0 (Sender):

* IP Address: 192.168.1.2
* Gateway: 192.168.1.1

### PC1 (Receiver):

* IP Address: 192.168.2.2
* Gateway: 192.168.2.1

---

## 🔬 Protocol Implementation

### 🟢 Stop and Wait Protocol

* Sender sends one packet at a time
* Waits for acknowledgment before sending next
* Simple but slow

---

### 🔵 Go-Back-N ARQ

* Sender sends multiple packets without waiting
* If error occurs, all packets from the error point are retransmitted
* Faster than Stop and Wait but less efficient on errors

---

### 🟣 Selective Repeat ARQ

* Sender sends multiple packets
* Only erroneous or lost packets are retransmitted
* Most efficient among the three

---

## 🧪 Simulation

### Data Transmission:

* ICMP (ping) used to simulate packet transfer

### Error Simulation:

* Network disruption introduced (disconnect cable)
* Packet loss observed

### Observation:

* Stop and Wait: One packet at a time
* Go-Back-N: Multiple packets retransmitted
* Selective Repeat: Only failed packets retransmitted

---

## 📊 Performance Analysis

| Protocol         | Throughput | Efficiency | Behavior                      |
| ---------------- | ---------- | ---------- | ----------------------------- |
| Stop and Wait    | Low        | Low        | One packet at a time          |
| Go-Back-N        | Medium     | Medium     | Retransmits multiple packets  |
| Selective Repeat | High       | High       | Retransmits only lost packets |

---

## 📊 Observations

* Stop and Wait has high delay due to waiting time
* Go-Back-N improves speed but wastes bandwidth on retransmission
* Selective Repeat provides best performance with minimal retransmission

---

## 📸 Screenshots

Screenshots included:

* Network topology
* Packet transmission
* Error simulation (packet loss)
* Simulation mode analysis

---

## 🚀 Conclusion

The simulation demonstrates how different flow control and error control protocols manage data transmission. Stop and Wait is simple but inefficient, Go-Back-N improves throughput, and Selective Repeat offers the best efficiency by retransmitting only lost packets.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---
