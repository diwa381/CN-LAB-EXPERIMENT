# 🌐 Sliding Window Protocol with Piggybacking

## 📌 Objective

To simulate the Sliding Window Protocol with Piggybacking using Cisco Packet Tracer and analyze its efficiency in data transmission and error control.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs (PC0 – Sender, PC1 – Receiver)
* 1 Switch

### Topology Design:

PC0 → Switch → PC1

---

## 🌐 IP Configuration

### PC0 (Sender):

* IP Address: 192.168.1.1
* Subnet Mask: 255.255.255.0

### PC1 (Receiver):

* IP Address: 192.168.1.2
* Subnet Mask: 255.255.255.0

---

## 🔬 Protocol Implementation

### 🟢 Sliding Window Protocol

* Allows sender to send multiple frames before receiving acknowledgment
* Improves data transmission efficiency
* Controls flow of data between sender and receiver

---

### 🟣 Piggybacking

* Acknowledgments are combined with outgoing data frames
* Reduces overhead by avoiding separate ACK packets
* Improves network efficiency

---

## 🧪 Simulation

### Data Transmission:

* Multiple packets sent from PC0 to PC1 using Add Simple PDU
* Continuous data flow observed

### Acknowledgments:

* PC1 sends acknowledgments back to PC0
* ACKs are combined with outgoing data (piggybacking)

### Visualization:

* Simulation Mode used to observe:

  * Packet flow
  * Window movement
  * Acknowledgments

---

## 📊 Observations

* Multiple packets transmitted simultaneously
* Sliding window moves as acknowledgments are received
* Piggybacking reduces number of separate ACK packets
* Efficient communication compared to Stop and Wait

---

## 📊 Analysis

| Feature    | Sliding Window        | Piggybacking           |
| ---------- | --------------------- | ---------------------- |
| Function   | Sends multiple frames | Combines ACK with data |
| Efficiency | High                  | Very High              |
| Delay      | Reduced               | Further reduced        |

---

## 📸 Screenshots

Screenshots included:

* Network topology
* Multiple packets in simulation
* Window movement
* Bidirectional data flow (piggybacking)

---

## 🚀 Conclusion

The Sliding Window Protocol significantly improves data transmission efficiency by allowing multiple frames to be sent without waiting for acknowledgments. Piggybacking further enhances performance by combining acknowledgments with outgoing data, reducing overhead and improving throughput.

---

## ⚠️ Note

Due to submission constraints, `.pkt` file is not included.
All configurations and results are documented with screenshots.

---
