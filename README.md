# Cisco-Packet-Tracer-Enterprise-Network
Multi-Site Enterprise Network using OSPF, DHCP, DNS, Web Server, Wireless Network and Branch Office Connectivity
🚀 Multi-Site Enterprise Network Design using Cisco Packet Tracer
📌 Project Overview

This project demonstrates the design and implementation of a Multi-Site Enterprise Network using Cisco Packet Tracer, connecting a Head Office and a Branch Office through multiple routers running OSPF Dynamic Routing.

The network integrates essential enterprise services such as DHCP, DNS, Web Server (SVNTube), Wireless Access Points, and Layer 2 Switching, providing seamless communication across multiple LANs and remote locations.

🏢 Network Architecture

The topology consists of:

Head Office
Four interconnected routers running OSPF
Multiple LAN segments
DHCP-enabled clients
Wireless Access Points
Local servers
WAN/ISP Connection
Cloud and DSL modem simulation
Router-to-router WAN links
Branch Office
Dedicated router and switch
DNS Server
Web Server (SVNTube)
Wireless clients
End-user devices

All networks are interconnected using OSPF, allowing automatic route discovery and dynamic path selection.

🔧 Key Features Implemented
🌍 Dynamic Routing
Multi-router topology using OSPF
Automatic route advertisement and learning
Full connectivity between Head Office and Branch Office
📡 DHCP Configuration
Automatic IP address allocation for clients
Simplified network management
Reduced manual configuration
🌐 DNS Server
Internal domain name resolution
Easy access to hosted services using domain names
Supports custom web applications
💻 Web Server (SVNTube)
Custom YouTube-style homepage
Hosted within the enterprise network
Accessible through DNS resolution
📶 Wireless Networking
Multiple Access Points deployed
Wireless laptops connected to enterprise LAN
Seamless wired and wireless communication
🔀 Switching Infrastructure
Cisco 2960 switches configured for LAN connectivity
PortFast enabled on access ports for faster device startup
Efficient Layer 2 forwarding
🔍 Network Verification
OSPF Neighbor relationships verified
End-to-end Ping testing completed
Successful communication across all subnets
📚 Technologies Used
Component	Technology
Network Simulator	Cisco Packet Tracer
Routing Protocol	OSPF
Routers	Cisco 2911
Switches	Cisco 2960
IP Management	DHCP
Name Resolution	DNS
Web Hosting	HTTP Web Server (SVNTube)
Wireless	Access Points
Protocol	IPv4
Switching	STP PortFast
🌐 Network Addressing Overview

The topology includes multiple LANs connected through OSPF with example networks such as:

192.168.1.0/24
192.168.2.0/24
192.168.3.0/24
192.168.4.0/24
172.16.1.0/24
172.16.2.0/24

WAN point-to-point links use dedicated subnets for router communication.

🖼️ Network Topology




The topology connects multiple routers, switches, servers, wireless access points, and client devices across Head Office and Branch Office locations using OSPF dynamic routing.

🧪 Testing & Validation

The following tests were successfully performed:

✅ OSPF Neighbor Establishment
✅ Router-to-Router Connectivity
✅ End-to-End Ping Verification
✅ DHCP IP Address Assignment
✅ DNS Name Resolution
✅ Access to SVNTube Web Page
✅ Wireless Client Connectivity
✅ Communication Between Head Office and Branch Office
📂 Repository Structure
Multi-Site-Enterprise-Network/
│
├── 3 router.pkt
├── README.md
├── images/
│   └── topology.png
├── configs/
│   ├── Router1.txt
│   ├── Router2.txt
│   ├── Router3.txt
│   └── SwitchConfigs.txt
└── documentation/
    └── Project_Report.pdf
🚀 How to Run the Project
Download or clone this repository.
Open 3 router.pkt using Cisco Packet Tracer 9.x or later.
Allow the network to initialize.
Verify OSPF neighbors using router CLI.
Test connectivity with ping between different LANs.
Open the browser on any client PC and access the configured SVNTube website through the DNS server.
Validate DHCP address allocation and wireless connectivity.
🎯 Skills Demonstrated
Enterprise Network Design
Dynamic Routing (OSPF)
Router Configuration
Switch Configuration
DHCP Deployment
DNS Configuration
Web Server Integration
Wireless Network Implementation
IPv4 Addressing & Subnetting
Spanning Tree PortFast
Network Troubleshooting
End-to-End Connectivity Testing
🔮 Future Enhancements
SSH Remote Management
VLAN Segmentation
Inter-VLAN Routing
NAT/PAT Configuration
Access Control Lists (ACLs)
EtherChannel
SNMP Monitoring
FTP & Email Server Integration
IPv6 Deployment
👨‍💻 Author

Praveen

Passionate about Networking, Cisco Technologies, and Enterprise Infrastructure Design.

⭐ Project Highlights
🌍 Multi-Site Enterprise Architecture
🔀 OSPF Dynamic Routing
📡 DHCP & DNS Integration
💻 Custom SVNTube Web Server
📶 Wireless Networking
🏢 Head Office ↔ Branch Office Connectivity
🛠️ Real-world Enterprise Simulation in Cisco Packet Tracer

If you found this project interesting, feel free to ⭐ star the repository and explore the topology!
