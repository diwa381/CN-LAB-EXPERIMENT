# CN-LAB-EXPERIMENT-9

# Packet Tracer Lab Report: PC–Switch–Server Communication

## Aim
To design a simple network using a PC, Switch, and Server, assign IP configurations, and analyze data transmission using TCP and UDP protocols in simulation mode.

---

## Part A: Network Configuration and TCP Analysis

### Step 1: Designing the Network
1. Launch Cisco Packet Tracer.
2. Add the following devices to the workspace:
   - One PC
   - One Switch
   - One Server
3. Use **Copper Straight-Through cables** to connect:
   - PC to Switch
   - Server to Switch

---

### Step 2: Configuring IP Addresses

#### PC Configuration:
- Navigate to: Desktop → IP Configuration  
- Set:
  - IP Address: `192.168.1.2`
  - Subnet Mask: `255.255.255.0`

#### Server Configuration:
- Navigate to: Desktop → IP Configuration  
- Set:
  - IP Address: `192.168.1.3`
  - Subnet Mask: `255.255.255.0`

---

### Step 3: Activating Web Service on Server
1. Open Server settings.
2. Go to **Services** tab.
3. Select **HTTP**.
4. Enable the service by turning it **ON**.

---

### Step 4: Entering Simulation Mode
1. Click on **Simulation Mode** from the bottom panel.
2. Access the **Event List Filters** section.

---

### Step 5: Adjusting Simulation Filters
1. Clear all pre-selected filters.
2. Enable only the following:
   - **TCP**
   - **HTTP**
3. Ensure:
   - **IPv4** is enabled
   - **Miscellaneous (Misc)** is enabled

---

### Step 6: Running the TCP Simulation
1. Open PC → Desktop → Web Browser.
2. Enter the Server IP: `192.168.1.3`
3. Click **Go** to initiate communication.
4. Observe:
   - TCP three-way handshake
   - HTTP request and response cycle

---

## Part B: UDP Analysis

### Step 7: Changing Protocol Filters
1. Go back to **Event List Filters**.
2. Disable **TCP**.
3. Enable **UDP**.
4. Keep **IPv4** and **Misc** enabled.

---

### Step 8: Executing UDP Simulation
1. Restart the simulation.
2. Monitor packet flow.
3. Key observations:
   - No connection establishment (no handshake)
   - Faster transmission
   - Less reliability compared to TCP

---

## Result
- The network was successfully created and configured.
- TCP communication demonstrated reliable data transfer with connection setup.
- UDP communication showed faster but connectionless transmission.

---

## Conclusion
This experiment helped in understanding basic networking setup and highlighted the functional differences between TCP and UDP protocols through simulation.
