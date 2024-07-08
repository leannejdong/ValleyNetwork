# ValleyNetwork

### Identifying Hardware and Software Components

#### Hardware Components:
1. **Router**: A high-quality router with robust security features to manage and direct network traffic.
2. **Firewall**: A dedicated hardware firewall to filter incoming and outgoing traffic and prevent unauthorized access.
3. **Switch**: A managed switch to connect and manage the network devices, ensuring efficient data transfer and network segmentation.
4. **Access Points**: Multiple Wi-Fi access points to provide wireless connectivity throughout the office.
5. **Server**: A secure server to host critical applications, data, and services.
6. **Network Attached Storage (NAS)**: For centralized and secure data storage with backup capabilities.
7. **Uninterruptible Power Supply (UPS)**: To ensure continuous power supply and protect hardware from power surges and outages.
8. **Endpoint Devices**: Secure desktops, laptops, and other devices for each of the 11 employees.
9. **Network Cables**: High-quality Ethernet cables for reliable wired connections.
10. **Security Cameras**: To monitor physical security of the network infrastructure.

#### Software Components:
1. **Antivirus/Anti-malware Software**: To protect all endpoint devices from malicious software.
2. **Network Monitoring Software**: To continuously monitor network traffic and detect any anomalies.
3. **Virtual Private Network (VPN)**: To enable secure remote access to the network.
4. **Intrusion Detection System (IDS)/Intrusion Prevention System (IPS)**: To detect and prevent network security threats.
5. **Access Control Software**: To manage user permissions and access to network resources.
6. **Data Encryption Tools**: To encrypt sensitive data both in transit and at rest.
7. **Patch Management Software**: To ensure all devices and software are up to date with the latest security patches.
8. **Backup Software**: To automate data backups and ensure data recovery in case of data loss.
9. **Security Information and Event Management (SIEM)**: To aggregate and analyze security events and logs.

### Network Configuration Diagram

* Insert a diagram here showing the configuration of the identified components.
* Include the router, firewall, switch, server, NAS, access points, endpoint devices, UPS, and security cameras.
* Illustrating their connections and placements.

  In Cisco Packet Tracer, the network diagram would visually represent the connectivity and arrangement of your network components. Here’s a rough idea of how your setup might look:

### Visual Representation in Cisco Packet Tracer

1. **Router**: Central device, usually placed at the top.
2. **Firewall**: Directly connected to the router, placed below it.
3. **Switch**: Connected to the firewall, placed below it.
4. **Access Points**: Connected to the switch, placed around the office layout.
5. **Server and NAS**: Connected to the switch, placed in the server area.
6. **PCs**: Connected to the switch, placed on desks.
7. **Security Cameras**: Connected to the switch, placed at strategic points.
8. **UPS**: Represented by annotations or connected to critical devices.

### Detailed Steps in Packet Tracer

#### Step 1: Adding Devices

- **Router**: Drag a router from the Network Devices section onto the workspace.
- **Firewall**: Drag a firewall or another router to represent the firewall.
- **Switch**: Drag a switch onto the workspace.
- **Access Points**: Drag multiple access points onto the workspace.
- **Server**: Drag a server onto the workspace.
- **PCs**: Drag 11 PCs onto the workspace.
- **NAS**: Drag another server or NAS device onto the workspace.
- **Security Cameras**: Drag IoT cameras or another end device onto the workspace.

#### Step 2: Connecting Devices

- Use the "Connections" tool to connect devices using Copper Straight-Through cables.
- Connect the Router to the Firewall.
- Connect the Firewall to the Switch.
- Connect the Switch to the Access Points, Server, NAS, PCs, and Security Cameras.

#### Step 3: Configuring Devices

- Double-click each device to open its configuration settings.
- Assign IP addresses, set up routing protocols, configure SSIDs, etc.

### Rough Layout

Here’s a rough visual representation (as an ASCII diagram) to give you an idea of the layout:

```plaintext
   [Router]
      |
   [Firewall]
      |
   [Switch]---------+
      |             |
    +--+--+         |
    |  |  |         |
[AP1][AP2][Server]  [NAS]
 |    |     |       |
[PC1][PC2] [PC3]  [PC4]
      ...    ...
[PC10][PC11] [Camera]
```

### Finalizing in Packet Tracer

#### Example Configuration:

1. **Router**: Assign an IP address and configure basic settings.
2. **Firewall**: Configure firewall rules and IP settings.
3. **Switch**: Set up VLANs if necessary and configure port settings.
4. **Access Points**: Set up wireless network settings (SSID, security).
5. **Server/NAS**: Configure storage settings and services.
6. **PCs**: Assign IP addresses and configure network settings.
7. **Security Cameras**: Configure IP settings and connect to the network.
8. **UPS**: Annotate its presence and connect critical devices.

#### Saving and Exporting:

- Save the project in Packet Tracer.
- Export the diagram as an image if needed.

This should give you a clear and organized layout of your office network in Cisco Packet Tracer, ready for further configuration and testing.


### Description of Components and Their Purpose

To secure the office network, various hardware and software components have been selected based on their functionalities and importance in maintaining network security.

**Router**: The router is the first line of defense, directing network traffic and providing basic security features such as Network Address Translation (NAT) and basic firewall capabilities.

**Firewall**: A dedicated hardware firewall is essential for filtering network traffic, preventing unauthorized access, and protecting the internal network from external threats.

**Switch**: A managed switch connects all network devices, allowing for efficient data transfer and network segmentation. This helps in isolating different parts of the network to enhance security.

**Access Points**: Wi-Fi access points provide secure wireless connectivity, ensuring that employees can connect to the network without compromising security.

**Server**: The server hosts critical applications and data, requiring robust security measures to protect against unauthorized access and data breaches.

**Network Attached Storage (NAS)**: NAS provides centralized data storage with backup capabilities, ensuring that important data is securely stored and easily accessible.

**Uninterruptible Power Supply (UPS)**: UPS devices protect network hardware from power surges and outages, ensuring continuous operation and preventing data loss.

**Endpoint Devices**: Secure desktops and laptops for each employee are equipped with antivirus and anti-malware software to protect against malicious attacks.

**Network Cables**: High-quality Ethernet cables ensure reliable and secure wired connections within the network.

**Security Cameras**: Monitoring the physical security of network infrastructure helps prevent unauthorized physical access and tampering.

**Antivirus/Anti-malware Software**: Protecting endpoint devices from malicious software is critical for maintaining network security.

**Network Monitoring Software**: Continuous monitoring of network traffic helps detect and respond to any security anomalies.

**Virtual Private Network (VPN)**: VPNs enable secure remote access, allowing employees to securely connect to the office network from remote locations.

**Intrusion Detection System (IDS)/Intrusion Prevention System (IPS)**: IDS/IPS solutions detect and prevent security threats, providing an additional layer of protection.

**Access Control Software**: Managing user permissions ensures that only authorized users have access to specific network resources.

**Data Encryption Tools**: Encrypting sensitive data both in transit and at rest prevents unauthorized access and data breaches.

**Patch Management Software**: Keeping all devices and software up to date with the latest security patches is crucial for protecting against known vulnerabilities.

**Backup Software**: Automated backups ensure that data can be recovered in case of data loss, providing continuity and resilience.

**Security Information and Event Management (SIEM)**: SIEM solutions aggregate and analyze security events and logs, providing valuable insights into potential security incidents and helping to coordinate responses.



