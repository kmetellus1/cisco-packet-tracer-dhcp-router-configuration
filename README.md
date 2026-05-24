<img width="905" height="547" alt="IP " src="https://github.com/user-attachments/assets/4dcfa2ad-a092-4e95-8031-7bdde13695b3" />
# cisco-packet-tracer-dhcp-router-configuration
Cisco Packet Tracer project demonstrating DHCP router configuration, IP address assignment, and network connectivity testing.
# Cisco Packet Tracer DHCP Router Configuration Project

## Project Overview

This project demonstrates a basic network configuration using Cisco Packet Tracer. The goal of the lab was to configure a wireless router to dynamically assign IP addresses to multiple PCs using DHCP, then verify network connectivity using `ipconfig` and `ping`.

This project shows hands-on networking skills that are important for IT support, help desk, network support, and entry-level cybersecurity roles.

## Objective

The objective of this project was to configure DHCP on a router, connect multiple client devices, verify that each device received an IP address automatically, and confirm that the devices could communicate across the network.

## Tools Used

- Cisco Packet Tracer
- Wireless router
- Client PCs
- DHCP configuration
- Command Prompt
- `ipconfig`
- `ping`

## Network Configuration

The router was configured with the following network settings:

- Router IP Address: `192.168.5.1`
- Subnet Mask: `255.255.255.0`
- DHCP Server: Enabled
- DHCP Starting IP Address: `192.168.5.126`
- Maximum Number of Users: `75`

The PCs were configured to receive IP addresses automatically using DHCP.

## Skills Demonstrated

- Cisco Packet Tracer lab setup
- Basic router configuration
- DHCP server configuration
- IP addressing
- Subnet mask configuration
- Client device configuration
- Network connectivity testing
- Troubleshooting using command-line tools
- Documentation of technical steps

## Steps Performed

1. Opened Cisco Packet Tracer.
2. Added a wireless router and multiple PCs to the workspace.
3. Connected the PCs to the router.
4. Accessed the router configuration page using `192.168.5.1`.
5. Enabled DHCP on the router.
6. Set the DHCP starting IP address to `192.168.5.126`.
7. Set the maximum number of DHCP users to `75`.
8. Configured the PCs to use DHCP.
9. Verified IP address assignment using `ipconfig`.
10. Tested connectivity using the `ping` command.

## Screenshots

### Network Topology

[Click here to view screenshot](image-file-name.png)https://github.com/kmetellus1/cisco-packet-tracer-dhcp-router-configuration/blob/main/network%20connection1%20.png

### PC DHCP IP Configuration

![PC DHCP IP Configuration](screenshots/pc0-dhcp-ip-configuration.png)

### Router DHCP Configuration

![Router DHCP Configuration](screenshots/router-dhcp-configuration.png)

### IPConfig and Ping Test

![IPConfig and Ping Test](screenshots/pc2-ipconfig-ping-test.png)

## Verification Results

The DHCP configuration was successful because the client PCs received IP addresses from the router automatically.

The network connectivity test was also successful because the PCs were able to ping the router and communicate with other devices on the network.

Example results shown in the lab:

- PC received IP address: `192.168.5.127`
- Router default gateway: `192.168.5.1`
- Ping to router: Successful
- Ping to another PC: Successful
- Packet loss: `0%`

## What I Learned

This project helped strengthen my understanding of DHCP, IP addressing, subnet masks, default gateways, and basic network troubleshooting.

I also gained more experience using Cisco Packet Tracer to simulate real networking environments and verify network connectivity.

## Professional Relevance

This project is relevant to IT support, help desk, network support, and cybersecurity roles because it demonstrates the ability to configure basic network services, verify client connectivity, and troubleshoot IP-related issues.

## Key Takeaways

- DHCP allows devices to receive IP addresses automatically.
- The router can act as a DHCP server for connected clients.
- `ipconfig` is useful for checking assigned IP addresses.
- `ping` is useful for testing network connectivity.
- Proper documentation helps explain technical work clearly to employers and recruiters.
