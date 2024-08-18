# Cisco Packet Tracer Project: Network Topology and Routing

![Screenshot from 2024-08-18 22-22-26](https://github.com/user-attachments/assets/54dbfcb4-e2ea-45b6-bb8a-a3348ed004f6)


This project involves the creation of a network topology and routing configuration using Cisco Packet Tracer. The primary goal of this project is to establish communication between various network devices, including routers, switches, servers, and end-user devices.

## About the Project

The network topology consists of the following components and configurations:

- **Routers**: The project includes three 1941 series routers. The connections between these routers are configured using the RIPv2 routing protocol.
- **Switches**: 2960-24TT model switches are used to interconnect various devices within the network.
- **Servers**: The network includes DHCP, DNS, HTTP, and Email servers.
- **Wireless Network**: A wireless network is established using an Access Point (AP), connecting laptops and PCs wirelessly.
- **PCs and Laptops**: Different subnets contain PCs and laptops, some connected via wired and others via wireless connections.
- **Printer**: A single printer is included in the network, with its IP address manually configured.

## Configuration Details

- **RIP Routing**: Dynamic routing between routers is enabled using the RIPv2 protocol.
- **DHCP**: The DHCP server is configured to automatically assign IP addresses to devices in the network.
- **DNS**: The DNS server is configured to resolve domain names to IP addresses.
- **HTTP**: The HTTP server provides web services.
- **Email**: The Email server is configured to provide email services using SMTP/POP3/IMAP protocols.
- **VLAN**: VLAN configuration is implemented on the switches to isolate certain devices within the network.

## Setup and Usage

1. **Opening the Project in Packet Tracer**:
   - Launch Cisco Packet Tracer.
   - Use the `File > Open` option to load the `.pkt` project file.

2. **Verifying Network Functionality**:
   - Ensure that each device has obtained the correct IP address.
   - Test connectivity by pinging between devices.
   - Check access to the HTTP server using web browsers.
   - Verify email server access with email clients.

3. **Troubleshooting**:
   - If connectivity issues arise, check the configurations on routers and switches.
   - Ensure the DHCP server is operational and assigning IP addresses correctly.
   - If DNS resolution fails, verify the DNS server configuration.

## Project Files

- `222017034_Emir_Furkan_ULU_Sinav.pkt`: Cisco Packet Tracer project file.
- `README.md`: This document.

