# my_portfolio
This is my portfolio for cybersecurity




This will contiain the details of my projects and evidence of my capabilities in the field of cybersecurity


AltSchool Learning and Support  Centre Network Design
AltSchool, a leading educational institution, is expanding its operations and opening a new Trading Floor Support Centre. This new building will accommodate 600 staff members. As a key member of the Networks Team, you are tasked with designing and implementing a robust and future-proof network solution for this new facility.
The new building will have three floors, with two departments on each floor, as follows:
First Floor: Sales and Marketing Department (120 users expected), Human Resource and Logistics Department (120 users expected)
Second Floor: Finance and Accounts Department (120 users expected), Administrator and Public Relations Department (120 users expected)
Third Floor: ICT (120 users expected), Server Room (12 devices expected)
Your Key Requirements and Tasks:
Network Design and Implementation Tool:
Use Cisco Packet Tracer to design and implement the network solution.
Hierarchical Model with Redundancy:
Implement a hierarchical network model with redundancy at every layer. This includes using two routers and two multilayer switches to provide the necessary redundancy.
Internet Connectivity and Redundancy:
The network is expected to connect to at least two Internet Service Providers (ISPs) to provide redundancy.
Each router should be connected to both ISPs.
The company network will connect to the static, public IP addresses (Internet Protocol) provided by the two Internet providers: 195.136.17.0/30, 195.136.17.4/30, 195.136.17.8/30, and 195.136.17.12/30.
Wireless Network:
Each department is required to have a wireless network for its users.
VLAN and Subnetting:
Each department should be in a different VLAN and a different subnet.
Given a base network of 172.16.1.0, carry out subnetting to allocate the correct number of IP addresses to each department, ensuring efficient use of the IP address space.
Basic Device Configuration:
Configure basic device settings such as hostnames, console password, enable password, and banner messages on all network devices.
Disable IP domain lookup.
Inter-VLAN Routing:
Devices in all departments are required to communicate with each other using the respective multilayer switches configured for inter-VLAN routing.
Multilayer Switch Functionality:
The multilayer switches are expected to carry out both routing and switching functionalities, and thus will be assigned IP addresses.
Dynamic IP Addressing (DHCP):
All devices in the network, with the exception of server room devices, are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server room.
Static IP Addressing (Server Room):
Devices in the server room are to be allocated IP addresses statically.
Routing Protocol:
Use OSPF as the routing protocol to advertise routes on both the routers and multilayer switches.
Remote Access Security:
Configure SSH on all routers and layer 3 switches for secure remote login.
Port-Security:
Configure port-security for the Finance and Accounts department to allow only one device to connect to a switchport. Use the "sticky" method to obtain MAC addresses, and set the violation mode to "shutdown".
Network Address Translation (NAT):
Configure PAT (Port Address Translation) to use the respective outbound router interface IPv4 address. Implement the necessary ACL (Access Control List) rule for this.
Communication Testing:
Test communication thoroughly to ensure everything configured is working as expected across the entire network.
