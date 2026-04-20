# 🌐 Transport Layer Protocols Simulation (UDP, TCP, SCTP)

## 📌 Objective

To simulate and analyze transport layer protocols (UDP, TCP, and SCTP) using Cisco Packet Tracer and compare their performance in terms of connection establishment, data transmission, and reliability.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* Multiple PCs (at least 6 devices)
* 1 Switch
* 1 Server (for TCP communication)

### Topology Design:

All PCs are connected to a central switch to enable communication between multiple sender-receiver pairs.

---

## 🌐 IP Configuration

Example configuration:

* PC0 → 192.168.1.1
* PC1 → 192.168.1.2
* PC2 → 192.168.1.3
* PC3 → 192.168.1.4
* PC4 → 192.168.1.5
* PC5 → 192.168.1.6
* Server → 192.168.1.100

Subnet Mask: 255.255.255.0

---

## 🔬 Protocol Implementation

### 🔵 UDP (User Datagram Protocol)

* Connectionless protocol
* Data sent without establishing connection
* Fast but unreliable
* Simulated using ping (ICMP)

---

### 🟢 TCP (Transmission Control Protocol)

* Connection-oriented protocol
* Uses handshake mechanism (SYN, ACK)
* Reliable data transmission
* Simulated using web browser (HTTP request)

---

### 🟣 SCTP (Stream Control Transmission Protocol)

* Supports multiple data streams
* Reliable like TCP but more efficient
* Simulated using multiple simultaneous transmissions

---

## 🧪 Simulation

### UDP Simulation:

* Ping command used to send packets
* Observed direct transmission without connection setup

### TCP Simulation:

* Web browser used to connect to server
* Observed connection establishment and data exchange

### SCTP Simulation:

* Multiple packets sent simultaneously between devices
* Observed parallel communication streams

---

## 📊 Observations

* UDP sends data quickly but without guarantee of delivery
* TCP ensures reliable communication through acknowledgments
* SCTP supports multiple streams and improves efficiency
* TCP introduces delay due to connection setup
* UDP has minimal delay but lacks reliability

---

## 📊 Analysis

| Protocol | Type                | Speed  | Reliability | Use Case               |
| -------- | ------------------- | ------ | ----------- | ---------------------- |
| UDP      | Connectionless      | Fast   | Low         | Streaming, gaming      |
| TCP      | Connection-oriented | Medium | High        | Web, file transfer     |
| SCTP     | Multi-stream        | High   | Very High   | Advanced communication |

---

## 📸 Screenshots

Screenshots included:

* Network topology
* Ping (UDP communication)
* Web server communication (TCP)
* Simulation mode packet flow

---

## 🚀 Conclusion

The simulation demonstrates the differences between transport layer protocols. UDP provides fast communication without reliability, TCP ensures accurate and ordered delivery, and SCTP enhances performance by supporting multiple streams. Each protocol is suited for different types of applications based on speed and reliability requirements.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---
