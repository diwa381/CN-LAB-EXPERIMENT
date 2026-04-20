# 🌐 DNS and DDNS Simulation

## 📌 Objective

To simulate Domain Name System (DNS) and Dynamic DNS (DDNS) using Cisco Packet Tracer and demonstrate how domain names are resolved and updated dynamically.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs (clients)
* 1 Server (DNS + HTTP)
* 1 Switch

### Topology Design:

PC0 → Switch → Server
PC1 → Switch

---

## 🌐 IP Configuration

### Server:

* IP Address: 192.168.1.1
* Subnet Mask: 255.255.255.0

### PC0:

* IP Address: 192.168.1.2
* DNS Server: 192.168.1.1

### PC1:

* IP Address: 192.168.1.3
* DNS Server: 192.168.1.1

---

## 🔬 DNS Configuration

* DNS service enabled on server
* Records created:

| Domain Name | IP Address  |
| ----------- | ----------- |
| example.com | 192.168.1.1 |
| test.com    | 192.168.1.3 |

---

## 🧪 Simulation

### DNS Query:

* PC0 used web browser to access:

  ```
  example.com
  ```
* Successfully resolved to server IP

### Command Line Query:

* PC1 used:

  ```
  nslookup test.com
  ```
* Received correct IP address

---

## 🔁 DDNS Implementation

### Add New Record:

```id="dnsadd"
newsite.com → 192.168.1.4
```

### Update Existing Record:

```id="dnsupdate"
example.com → 192.168.1.5
```

---

## 🧪 Verification

* Used `nslookup` to verify updated records
* Used browser to access new domain

---

## 📊 Observations

* DNS converts domain names into IP addresses
* DDNS allows updating records dynamically
* Changes in DNS records are reflected immediately
* DNS improves usability of networks

---

## 📊 Analysis

| Feature     | DNS             | DDNS            |
| ----------- | --------------- | --------------- |
| Function    | Name resolution | Dynamic updates |
| Flexibility | Static          | High            |
| Efficiency  | Moderate        | High            |

---

## 📸 Screenshots

Screenshots included:

* DNS configuration table
* Successful domain access
* nslookup results
* Updated DNS records

---

## 🚀 Conclusion

The simulation demonstrates how DNS simplifies communication using domain names and how DDNS enables dynamic updates in changing network environments. DNS is essential for usability, while DDNS improves flexibility.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---


