# 🌐 Multiple Access Protocols Simulation

## 📌 Objective

To design and simulate multiple access protocols including Pure ALOHA, Slotted ALOHA, CSMA/CD, and CSMA/CA using Cisco Packet Tracer, and analyze their performance in handling collisions and improving data transmission efficiency.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* Multiple PCs (4–6 devices)
* Hub (for ALOHA protocols)
* Switch (for CSMA/CD)
* Wireless Router (for CSMA/CA)

### Topology Design:

All devices are connected through a shared medium to simulate real-world communication.

---

## 🌐 IP Configuration

Example configuration:

* PC0 → 192.168.1.1
* PC1 → 192.168.1.2
* PC2 → 192.168.1.3
* PC3 → 192.168.1.4

Subnet Mask: 255.255.255.0

---

## 🔬 Protocol Implementation

### 🟢 Pure ALOHA

* Devices transmit data anytime without checking channel
* High probability of collisions
* Low efficiency

---

### 🔵 Slotted ALOHA

* Time divided into slots
* Devices send data at specific intervals
* Reduced collisions compared to Pure ALOHA

---

### 🟠 CSMA/CD (Carrier Sense Multiple Access with Collision Detection)

* Devices check channel before sending
* Detect collisions and retransmit
* Used in wired Ethernet networks

---

### 🟣 CSMA/CA (Carrier Sense Multiple Access with Collision Avoidance)

* Devices avoid collisions before transmission
* Uses waiting time and acknowledgments
* Used in wireless networks

---

## 🧪 Simulation

### Data Transmission:

* ICMP (ping) used to generate traffic between devices

### Collision Simulation:

* Multiple packets sent simultaneously to create collisions
* Network conditions varied to observe behavior

### Observation:

* Collisions observed in hub-based network
* Reduced collisions in switch-based network
* Minimal collisions in wireless setup

---

## 📊 Performance Analysis

| Protocol      | Collision Rate | Efficiency | Usage             |
| ------------- | -------------- | ---------- | ----------------- |
| Pure ALOHA    | High           | Low        | Basic systems     |
| Slotted ALOHA | Medium         | Moderate   | Improved ALOHA    |
| CSMA/CD       | Low            | High       | Wired networks    |
| CSMA/CA       | Very Low       | Very High  | Wireless networks |

---

## 📊 Observations

* Pure ALOHA shows frequent collisions
* Slotted ALOHA reduces collision probability
* CSMA/CD detects and handles collisions efficiently
* CSMA/CA avoids collisions before transmission

---

## 📸 Screenshots

Screenshots included:

* Hub-based collision scenario
* Switch-based communication
* Wireless network setup
* Simulation packet flow

---

## 🚀 Conclusion

The simulation demonstrates how different multiple access protocols manage shared communication channels. Pure ALOHA is inefficient due to high collisions, while CSMA/CD and CSMA/CA significantly improve performance. CSMA/CA provides the best efficiency in wireless environments.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---
