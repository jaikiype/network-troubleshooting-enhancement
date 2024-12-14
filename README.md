# Network Troubleshooting and Enhancement Assignment

## Objective
This project focuses on troubleshooting and enhancing a partially functioning network using **Cisco Packet Tracer**. The primary tasks include:
- Fixing DHCP issues.
- Adding new users.
- Implementing basic security and network features to ensure the network is fully operational.

---

## Network Overview
The network topology consists of the following components:
- **Router:** 2911 Router (Router0)
- **Switch:** 2960 Switch (Switch0)
- **Access Points:** Admin/IT, Access Point1, and Access Point2
- **Devices:** PCs (PC0, PC1, PC2, PC3, PC4, PC5) and Printers (Printer0, Printer1, Printer2)

![Network Topology](image.png)

---

## Tasks

### 1. Fix DHCP Issues
- Troubleshoot and resolve incomplete DHCP configurations on **Router0**.
- Ensure all devices receive proper IP addresses dynamically via DHCP.

### 2. Fix Connectivity Issues
- Analyze and resolve connectivity issues due to misconfigurations in the network setup.

### 3. Add Additional Users
- Expand the network to accommodate additional devices/users.

### 4. Implement Security Features
- Apply basic security measures:
  - **Port Security**
  - **Password Protection**
  - **Firewall Rules**

---

## Network Configurations

### Router Configuration
Key settings for the **2911 Router (Router0):**
- VLAN interfaces with respective IP ranges:
  - VLAN 10: 192.168.1.62/26
  - VLAN 20: 192.168.1.126/26
  - VLAN 30: 192.168.1.190/26
  - VLAN 115: 192.168.50.1/24

### Switch Configuration
The **2960 Switch (Switch0)** is configured with multiple VLANs:
- VLAN 10, 20, 30, and 115 assigned to respective ports.
- Port-to-VLAN mappings ensure efficient segmentation and communication.

---

## Key Features Implemented
1. **DHCP Configuration:**
   - Multiple DHCP pools were configured on **Router0** to support different VLANs.
   - Verified with `show run | section dhcp`.

2. **VLAN Configuration:**
   - Configured VLANs for effective network segmentation.
   - Verified with `show vlan brief`.

3. **MOTD (Message of the Day):**
   - Configured a message for both the router and the switch for authentication and identification.

---

## How to Use
1. Open the provided **Cisco Packet Tracer** file.
2. Follow the network topology and inspect the configurations.
3. Test and verify the network functionalities:
   - DHCP leases.
   - Device connectivity (e.g., pings between devices).
   - Security features (e.g., user access verification and restricted ports).

---

## Author
**Jaik Iype**  
ID Number: 24159379
