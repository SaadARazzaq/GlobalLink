# GlobalLink
## A Computer Networks Lab Project

This project focused on designing and configuring a computer network using the Cisco Packet Tracer V6.0.1. The goal was to implement various networking concepts such as VLSM (Variable Length Subnet Masking) for efficient IP address allocation, IP addressing, routing protocols, VLANs, DHCP, NAT, and inter-VLAN communication.

## Project Goals

The main objectives of this project are:

- Configure the network according to the provided layout and documentation.
- Perform VLSM to allocate IP addresses based on the number of required hosts per subnet.
- Utilize EIGRP, OSPF, and RIP as the routing protocols in different network blocks.
- Enable redistribution of routes between different routing protocols.
- Implement DHCP servers for IP address assignment to hosts.
- Set up VLANs as specified in the scenario.
- Establish VLAN Trunking Protocol (VTP) with one switch acting as a server and others as clients.
- Enable inter-VLAN communication between specific VLANs.
- Implement NAT for external network access.
- Create an aesthetically pleasing physical workspace using the Packet Tracer simulator.

## Approach

To achieve the project goals, we followed these steps:

1. Analyzed the IP address file to determine the network addresses for each block.
2. Applied VLSM to allocate IP addresses based on the number of required hosts per subnet.
3. Configured routers in each block to use the appropriate routing protocols (EIGRP, OSPF, RIP) as specified.
4. Implemented route redistribution between different routing protocols on designated routers.
5. Set up DHCP servers for IP address assignment to hosts, considering separate servers for different VLANs.
6. Configured VLANs on the switches to ensure proper segregation and communication within each VLAN.
7. Established VTP, with one switch acting as the server and others as clients.
8. Enabled inter-VLAN communication between specific VLANs using inter-VLAN routing.
9. Implemented NAT on the designated router using the provided private IP address range.

## Bonus Points

To earn bonus points, we focused on creating an attractive physical view of the network topology embedded in a real-world environment. Incorporated background images, cities, buildings, and offices to enhance the visual representation of the project.

## Getting Started

To run or simulate the network, follow these instructions:

1. Install the Cisco Packet Tracer (version 6.0.1).
2. Clone this Repo.
3. Run the pkt file.

## Authors

- [Mustafa Aqeel](https://github.com/mustafaaqeel)
- [Muhammad Wasif](https://github.com/wasifmohammad)
- [Saad Abdur Razzaq](https://github.com/saadarazzaq)


