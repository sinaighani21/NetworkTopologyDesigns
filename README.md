# Network Topology Designs
Here you will see some of my Network Topology designs which I used Cisco Packet Tracer.

<h1>Algonquin College Network Topology Example</h1>
<p align="center">
<img src="https://i.imgur.com/sagYaob.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Algonquin College is a large college which has 3 campuses in Ontario Canada. The college’s students and staff are distributed in 4 facilities; these include the facilities of Health and Science; Business; Engineering/Computing and Art/Design. Each member of staff has a PC, and students have access to PCs in the library and labs.


Requirements: 

A.	Create a network topology with the main components to support the following: 
•	Main Campus:
•	Building C: Administrative staff in the departments of management, HR and finance. The admin staff PCs are distributed in the building offices, and it is expected that they will share some networking equipment (Hint: use of VLAN’s is expected here). The faculty of business is also situated in this building.
•	Building A: Faculty of engineering and computing and faculty of Art and Design

•	Building T: Students labs and IT department. The IT department hosts the College’s Web server and other servers.
•	There is also an email server hosted externally on the cloud.


B.	Smaller Campuses
•	Faculty of Health and Science (Staff and Student labs are placed on separate floors)



C.	You will be expected to configure the core devices and few end devices to provide end-to-end connectivity and access to the internal servers and the external server.
•	Each department/faculty is expected to be on its own separate IP network.
•	The switches should be configured with appropriate VLAN’s and security settings.
•	RIPv2 will be used to provide routing for the routers in the internal network and static routing for the external network.
•	The devices in building A will be expected to acquire dynamic IP addresses from a router-based DHCP server.


Tasks:
Task 1: Your task is to plan, design, and prototype the network topology for Algonquin College’s network using cisco packet tracer. Formative feedback will be gives on this task in week 6.

Task 2: Configure the network using Packet Tracer with appropriate settings to achieve the connectivity and functionalities specified in the requirements. 
Task 3: Produce a report (max 1500 words) including evaluation of your proposed network design and critical appraisal on your work. Your evaluation should include performance, scalability, reliability and security of your proposed network. 




<h1>Enterprise Networking Topology Example</h1>
<p align="center">
<img src="https://i.imgur.com/5I55LGZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Cyber Security Enterprise Networking 
By: Sina Ig

A Cyber Security Operation Center support employs 700 staff. They have recently expanded and as a result, they need to move to a new building. A building has been identified but has no network. This means that before they move out, the network service needs to be designed and implemented in the new building. Existing network compromise of the following elements: 
The new building is expected to have three floors with two departments in each for example:
1.	First floor (Sales and Marketing department-120 users expected. Human Resources and Logistics Department-120 users expected)
2.	Second Floor (Finance and Accounts Department-120 users expected, Administrator and Public Relations Department-120 users expected)
3.	Third floor (ITS-120 users expected, Server room- 12 devices expected)

Therefore, as a key member of the Networks team, you have been tasked to design a network for the new building. At this stage, logical design is required, which shows the measures that you would put in place to ensure that the new networks meet the current business need and is future proofed.

Requirements
1.	Use Cisco Packet Tracer to design and implement the network solution.
2.	Use hieratical model providing redundancy ay every layer i.e. two routers and two multilayer switches are expected to be used to provide redundancy.
3.	The network is also expected to connect at least two ISPs to provide redundancy and each router to be connected to the two ISP’s.
4.	Each department is required to have a wireless network for the users.
5.	Each department should be in a different VLAN and in different Subnetwork.
6.	Provide a base network of 172.16.1.0, carry out subnetting to allocate the correct number of IP addresses to each department.
7.	The company network is connected to the static, public IP addresses (Internet Protocol) 195.136.17.0/30, 195.136.17.4/30, 195.136.17.8/30 and 195.136.17.12/30    connected to the two internet providers.
8.	Configure basic device settings such as hostnames, console passwords, enable password, banner messages, disable IP domain lookup.
9.	Devices in all the departments are required to communicate with each other with the respective multilayer switch configured for inter-VLAN routing.
10.	The Multilayer switches are expected to carry out both routing and switching functionalities thus will be assigned IP addresses.
11.	All devices in the network are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server room.
12.	Devices in the server room are to be allocated IP address statically. 
13.	Use OSPF as the routing protocol to advertise routes both on the routers and multilayer switches.
14.	Configure SHH in all the routers and layer 3 switches for remote login.
15.	Configure port-security for the Finance and Accounts departments to allow only one device to connect to the switchport, use sticky method to obtain mac-address and violation mode shutdown.
16.	Configure PAT to use the respective outbound router interface IPv4 address, implement the necessary ACL rules.
17.	Test connectivity and communication to ensure everything is configured as expected.



################ Configuration Steps ################## 

1.	Basic settings on all devices plus SSH on the routers and 13 switches.
2.	VLANs assignment plus all access and trunk ports on 12 and 13 switches.
3.	Switchport security on FINANCE department.
4.	Subnetting and IP addressing. 
5.	OSPF on the routers and 13 switches.
6.	Static IP address on the Server Room devices.
7.	DHCP Server device configurations.
8.	Inter-VLAN routing on the 13 switches plus IP DHCP helper addresses.
9.	Wireless network configuration.
10.	PAT + Access Control List
11.	Verify & test connectivity.




<h1>Hotel Network Management Design</h1>
<p align="center">
<img src="https://i.imgur.com/mh7Fngz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Hotel Management Network Design and Implementation
By: Sina Ig

As a part of the networking project, you are required to design and implement Modern Hotel Network. The hotel has three floors; on the first floor there are three departments (Reception, stores and logistics), on the second floor there are three departments (Finance, HR and Sales/Marketing), while the third-floor hosts IT and Administrations. Therefore, the following are the parts of the considerations during the design and implementation.
1.	There should be three routers connected to each floor (all placed in the server room in the IT department).
2.	All routers should be connected to each other using serial DCE cable.
3.	The networks between the routers should be 10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30 
4.	Each floor is expected to have one switch (placed in the respective floor).
5.	Each floor is expected to have WIFI networks connected to laptops and phones.
6.	Each department is expected to have at least one printer.
7.	Each department is expected to be in a different VLAN with the following details

1st floor.
•	Reception: VLAN 80, Network: 192.168.8.0/24
•	Store: VLAN 70, Network: 192.168.7.0/24
•	Logistics: VLAN 60, Network: 192.168.6.0/24


2nd floor.
•	Finance: VLAN 50, Network: 192.168.5.0/24
•	HR: VLAN 40, Network: 192.168.4.0/24
•	Sales: VLAN 30, network: 192.168.3.0/24


3rd floor.
•	Administration: VLAN 20, Network: 192.168.2.0/24
•	IT Team: VLAN 10, Network: 192.168.1.0/24



8.	Use OSPF as the routing protocol to advertise routes
9.	All devices on the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
10.	All the devices on the network are expected to communicate with each other.
11.	Configure SSH on all the routers for remote login.
12.	In the IT department, add a PC called TEST-PC to port Fa/0/1 and use it to test remote login.
13.	Configure port security on IT department switch to allow only TEST-PC to access port Fa0/1 (use sticky method to obtain mac-address with violation mode of shutdown).





<h1>SOHO (Small Office Home Office) Project Design Topology</h1>
<p align="center">
<img src="https://i.imgur.com/GwbrumJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Small Office Home Office / SOHO Network Design & Implementation Project 
by: Sina Ig

Foot Locker company is a fast-growing company in North America with more than 85 million customers globally. The company deals with selling and buying of food items, which are basically operated from the headquarters. The company is intending to open a branch near the local village in Ottawa. Thus, the company requires fresh IT graduated to design the network for the branch, the network is intended to operate separately from the HQ network.


Being a small network, the company has the following requirements during implementation.
a)	One router and one switch to be used (all CISCO products).
b)	3 departments (Admin/IT, Finance/HR and customer service/Reception)
c)	Each department is required to be different in VLANS.
d)	Each department is required to have wireless network for the users.
e)	Host devices in the network are required to obtain IPv4 address automatically.
f)	Devices in all the departments are required to communicate with each other.
Assume the ISP gave out a base network of 192.168.1.0, you as a network engineer who has been hired, design and implement a network considering the above requirements.


Base network: 192.168.1.0
Number of subnets = 3
Number of subnets = 2^n
2^n = 3 == n=2
Class C = 255.255.255.0 => 11111111.11111111.11111111.00000000
After borrowing 2 bits
New binary = 11111111.11111111.11111111.11000000
New Subnet = 255.255.255.192
Block size = 64

1st Subnet
Network ID: 192.168.1.0
Broadcast ID: 192.168.1.63
Host range: 192.168.1.1 – 192.168.1.62


2nd Subnet
Network ID: 192.168.1.64
Broadcast ID: 192.168.1.127
Host range: 192.168.1.65 – 192.168.1.126


3rd Subnet
Network ID: 192.168.1.128
Broadcast ID: 192.168.1.191
Host range: 192.168.1.129 – 192.168.1.190


