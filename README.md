# Company-X
<img width="1897" height="818" alt="Screenshot 2026-03-29 202554" src="https://github.com/user-attachments/assets/dfa16667-a65e-4325-976d-edfa529b5202" />

1. Physical Topology
WAN Connections

The project connects three Cisco 2911 Router devices using serial cables.
This setup simulates communication between geographically separated locations (WAN).

LAN Structure

The local network includes end devices such as:

Server1
PC4
Laptop4

These devices are connected through GigabitEthernet interfaces, ensuring high-speed data transfer within the local network.

Layer Distribution

A Cisco Catalyst 3560 multilayer switch is used to:

Connect different VLANs
Perform internal routing (Layer 3 switching)
2. Configuration and Protocols
Routing

The network uses the OSPF (Open Shortest Path First) protocol to dynamically connect the routers.
This ensures:

Automatic route updates
Selection of the shortest and fastest path
Network stability in case of link failure
VLAN Segmentation

The internal network is divided into multiple VLANs:

VLAN 10
VLAN 20
VLAN 30
VLAN 40

This segmentation provides:

Traffic isolation
Improved security
Better network performance
IP Addressing
Class C IP addresses (e.g., 192.168.x.x) are used for LANs
/30 subnet masks are used for point-to-point WAN links (e.g., 10.0.0.x) to minimize IP address waste
3. Project Objectives
Achieve full connectivity between all devices across different branches
Implement Inter-VLAN Routing using a Layer 3 switch
Ensure network stability and proper IP address management without conflicts
