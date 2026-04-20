# 🌐 Logical Addressing and Address Mapping (IPv4, IPv6, ARP, RARP, BOOTP, DHCP)

## 📌 Objective

To simulate logical addressing using IPv4 and IPv6 and demonstrate address mapping techniques such as ARP, RARP, BOOTP, and DHCP using Cisco Packet Tracer.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs
* 1 Server (DHCP/BOOTP/RARP)
* 1 Router
* 1 Switch

### Topology Design:

PC0 → Switch → Router → Switch → PC1
Server connected to switch

---

## 🌐 IP Configuration

### IPv4 Addressing

#### PC0:

* IP Address: 192.168.1.2
* Subnet Mask: 255.255.255.0
* Gateway: 192.168.1.1

#### PC1:

* IP Address: 192.168.1.3
* Subnet Mask: 255.255.255.0
* Gateway: 192.168.1.1

---

### IPv6 Addressing

#### PC0:

* IPv6 Address: 2001:db8::1

#### PC1:

* IPv6 Address: 2001:db8::2

---

## 🔬 Address Mapping Techniques

### 🟢 ARP (Address Resolution Protocol)

* Converts IP address to MAC address
* Triggered using ping command
* ARP request and reply observed in simulation

---

### 🔵 RARP (Reverse Address Resolution Protocol)

* Converts MAC address to IP address
* Configured on server with MAC-to-IP mapping
* Used to assign IP to devices without configuration

---

### 🟠 BOOTP (Bootstrap Protocol)

* Assigns IP address from server
* Requires predefined configuration
* Less flexible than DHCP

---

### 🟣 DHCP (Dynamic Host Configuration Protocol)

* Automatically assigns IP addresses
* Uses Discover → Offer → Request → Acknowledge process
* Simplifies network configuration

---

## 🧪 Simulation

### ARP Simulation:

* PC0 pings PC1
* ARP request and response observed

### DHCP Simulation:

* PC set to DHCP mode
* Server assigns IP automatically

### BOOTP & RARP:

* Configured on server
* Address mapping observed

### IPv4 & IPv6 Communication:

* Successful ping between devices using both protocols

---

## 📊 Observations

* ARP resolves MAC addresses dynamically
* DHCP provides automatic IP assignment
* BOOTP works but requires manual setup
* RARP maps MAC to IP
* IPv6 provides modern addressing compared to IPv4

---

## 📊 Analysis

| Protocol | Function              | Efficiency |
| -------- | --------------------- | ---------- |
| ARP      | IP → MAC              | Fast       |
| RARP     | MAC → IP              | Limited    |
| BOOTP    | Static IP assignment  | Moderate   |
| DHCP     | Dynamic IP assignment | High       |

---

## 📸 Screenshots

Screenshots included:

* Network topology
* ARP request/response
* DHCP IP assignment
* IPv4 and IPv6 ping
* Simulation packet flow

---

## 🚀 Conclusion

The simulation demonstrates how devices acquire and resolve network addresses using different techniques. DHCP provides the most efficient solution for IP assignment, while ARP plays a key role in address resolution. IPv6 offers improved addressing compared to IPv4.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---

