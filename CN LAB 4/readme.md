# 🌐 Error Detection and Correction using Block Coding and CRC

## 📌 Objective

To simulate error detection and correction mechanisms using Block Coding and Cyclic Redundancy Check (CRC) in Cisco Packet Tracer.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs (PC0, PC1)
* 1 Switch

### Topology Design:

PC0 → Switch → PC1

---

## 🌐 IP Configuration

### PC0:

* IP Address: 192.168.1.1
* Subnet Mask: 255.255.255.0

### PC1:

* IP Address: 192.168.1.2
* Subnet Mask: 255.255.255.0

---

## 🔬 Implementation

### 🔹 Block Coding

* Data is divided into blocks before transmission
* Parity bits are added to each block
* Used to detect and correct single-bit errors

### 🔹 Cyclic Redundancy Check (CRC)

* Sender generates a checksum using a polynomial
* Receiver recalculates and compares checksum
* If mismatch occurs → error detected

---

## 🧪 Simulation

### Data Transmission:

* ICMP (ping) used to simulate communication
* Packets sent from PC0 to PC1

### Error Simulation:

* Network connection was intentionally disrupted
* Packet transmission failed (simulated error)

### Error Detection:

* Failed packets indicate error detection
* CRC ensures integrity check

---

## 📊 Observations

* Successful transmission occurs under normal conditions
* Packet loss observed when connection is disrupted
* Errors are detected when packets fail to reach destination
* CRC provides reliable error detection mechanism

---

## 📊 Analysis

| Method       | Function                    | Efficiency |
| ------------ | --------------------------- | ---------- |
| Block Coding | Detects single-bit errors   | Moderate   |
| CRC          | Detects multiple-bit errors | High       |

---

## 📸 Screenshots

Screenshots included:

* Network topology
* Successful packet transmission
* Error (packet loss)
* Simulation mode packet flow

---

## 🚀 Conclusion

The simulation demonstrates how error detection and correction mechanisms work in data communication. Block coding provides basic error detection, while CRC offers more robust and reliable detection of errors. These mechanisms are essential for ensuring data integrity in networks.

---

## ⚠️ Note

Due to submission constraints, `.pkt` file is not included.
All configurations and results are documented with screenshots.

---
