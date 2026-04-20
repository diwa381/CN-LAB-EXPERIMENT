# 🌐 HTTP and Web Server Simulation

## 📌 Objective

To simulate HTTP communication between a client and a web server using Cisco Packet Tracer and demonstrate how web pages are requested and delivered over the network.

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 🧩 Network Topology

The network consists of:

* 2 PCs (clients)
* 1 Server (web server)
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

### PC1:

* IP Address: 192.168.1.3

---

## 🔧 Server Configuration

### HTTP Service:

* Enabled HTTP service on server
* Created a simple HTML page:

```html
<html>
<body>
<h1>Welcome to My Web Server</h1>
<p>This is HTTP simulation in Cisco Packet Tracer</p>
</body>
</html>
```

---

## 🧪 Simulation

### Network Testing:

* Verified connectivity using:

  ```
  ping 192.168.1.1
  ```

### Web Access:

* PC0 opened web browser
* Entered:

  ```
  http://192.168.1.1
  ```
* Web page successfully loaded

---

## 🎥 HTTP Communication

### Request:

* Client sends HTTP GET request to server

### Response:

* Server sends HTML page as response

---

## 📊 Observations

* HTTP follows request-response model
* Client initiates communication
* Server responds with web content
* Communication is reliable using TCP

---

## 📊 Analysis

| Feature            | Description      |
| ------------------ | ---------------- |
| Protocol           | HTTP             |
| Transport Layer    | TCP              |
| Communication Type | Request-Response |
| Usage              | Web browsing     |

---

## 📸 Screenshots

Screenshots included:

* Network topology
* Web page display
* HTTP packets in simulation mode
* Server HTML configuration

---

## 🚀 Conclusion

The simulation demonstrates how HTTP enables communication between a client and a web server. The client sends a request, and the server responds with web content. This process forms the basis of web browsing in the World Wide Web.

---

## ⚠️ Note

Due to submission constraints, `.pkt` files are not included.
All configurations and results are documented with screenshots.

---
