# 🌐 Network Simulator using Cisco Packet Tracer

## 📌 Objective

To design and simulate a network to analyze packet delay, packet loss, and throughput using Cisco Packet Tracer.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs (PC0, PC1)
* 2 Switches
* 1 Router

### Network Design:

* Network 1: 192.168.1.0/24
* Network 2: 192.168.2.0/24

---

## 🌐 IP Configuration

### PC0:

* IP: 192.168.1.2
* Gateway: 192.168.1.1

### PC1:

* IP: 192.168.2.2
* Gateway: 192.168.2.1

---

## 🔧 Router Configuration

Configured router interfaces to connect two networks:

```id="b42k1m"
interface fastEthernet 0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

interface fastEthernet 0/1
ip address 192.168.2.1 255.255.255.0
no shutdown
```

---

## 🔁 Routing

* Static routing used to enable communication
* Packets forwarded between two networks

---

## 🧪 Simulation

* Used ping command to generate traffic
* Example:

  ```
  ping 192.168.2.2
  ```
* Simulation Mode used to observe packet flow

---

## 📊 Performance Analysis

### Packet Delay

* Observed using simulation timeline

### Packet Loss

* No loss in normal condition
* Loss observed when connection is broken

### Throughput

* Measured based on successful packet delivery

---

## 📸 Screenshots

Screenshots included:

* Network topology
* Successful ping
* Simulation packet flow

---

## 🚀 Conclusion

The network successfully demonstrated packet transmission between different networks using routing. Delay, loss, and throughput were analyzed under different conditions.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---
