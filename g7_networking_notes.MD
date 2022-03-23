# NETWORKING FUNDAMENTALS
Router
A router is a network device that connects multiple network segments into one network.

•	Connects multiple switches and their respective networks to form a larger network (basically, it acts as a switch between networks).

•	Can also filter the data that flows through it, which enables data to be routed differently, depending on need.


What is network?
A computer network is a collection of computing devices that are logically connected to communicate and share resources.
These are the main components of a computer network:
o	Client devices
o	Servers
o	Network adapters (NICs) and cables
o	Hubs and switches 
o	Routers

Questions:
•	1. Which network device should you use to connect multiple networks? 
Ans: Router
•	2. Which device makes a direct link (by using MAC addresses) between the transmitting device and receiving device?
Ans: Switch
•	3. Which type of cable transmits light instead of electricity?

Ans: Fiber-Optic

COAXIAL CABLE: 
•	A coaxial cable (or coax) contains a central conductor wire (typically copper) that is surrounded by an insulating material. This insulating material, in turn, is surrounded by a braided metal shield. The entire cable is then enclosed in a jacket. 
•	Today, the most common uses for coaxial cables are to connect a cable TV modem to an internet service provider (ISP), and to connect TVs to cable boxes.

TWISTED-PAIR
•	The most common type of computer, telephone, and network cable is known as a twisted-pair. It is more commonly known as an Ethernet cable. The cable consists of color-coded pairs of insulated copper wires that are bundled together in the same jacket. 
•	Twisted-pair cabling is available in two types: shielded (STP) and unshielded (UTP). Shielding further prevents electromagnetic interference.

Network hub or switch
A hub or switch is a device that connects all the nodes of a network together. Every hardwired device in the network uses a network adapter, or NIC, to connect directly to a port on the hub or switch through a single cable.
Hub
•	A device that transmits data that is received on one port to all the other ports on the hub. 
•	If one node sends data, all the others receive it, but only the intended recipient listens to it.

Switch
•	A device that transmits data to only the receiving device. It makes a direct link by using MAC addresses between the transmitting device and the receiving device.
•	It improves performance because it does not use bandwidth on unnecessary transmissions.

Local-area network (LAN)
•	A LAN connects devices in a limited geographical area, such as a floor, building, or campus. 
•	LANs commonly use the Ethernet standard for connecting devices, and they usually have a high data-transfer rate.
•	Wireless technology is also commonly used for a LAN.

Wide-area network (WAN)
•	A WAN connects devices in a large geographical area, such as multiple cities or countries. 
•	WANs are used to connect LANs. They use technologies such as fiber-optic cables and satellites to transmit data. 
•	The internet is considered to be the largest WAN.


Network management models
A network management model is a representation of how data is managed, and how applications are hosted in a network. The two most common network management models for a LAN are client-server and peer-to-peer. 

Client-server model
In a client-server network model, the data management and application hosting are centralized at the server and distributed to the clients. All clients on the network must use the designated server to access shared files and information that are stored on the serving computer. 
If the server goes down, no client can access the network until the server is restored. Examples of client-server models are:
•	File server and desktop clients
•	Print server and desktop clients

Peer-to-peer model
In a peer-to-peer network model, each node has its own data and applications and is responsible for its own management and security.
The peer-to-peer model is a distributed architecture that shares tasks or workloads among peers. Peers are equally privileged participants in the architecture. For example, files can be shared directly between systems on the network without a central server.
This model might be considered under the following conditions:
•	Users are responsible for backing up each node
•	Security requirements are not restrictive
Network topologies
Computer networks use different topologies to share information. A topology is a pattern (or diagram) that shows how nodes connect to each other. Computer networks have both physical topologies and logical typologies.
•	Physical topology – Refers to the physical layout of wires in the network
•	Logical topology – Refers to how data moves through the network


1.	Bus 
Physical topology
A bus topology positions all the devices on a network along a single cable. They run in a single direction from one end of the network to the other. A bus topology is also called a line topology or backbone topology. 
Logical topology
The data flow on the network also follows the route of the cable, and it moves in one direction. 
A bus topology is simple to configure. However, it allows only one computer to send a signal at a time, which can cause network collisions that bring down the network.
2.	Star 
Physical topology
A star topology is set up so that every node in the network is directly connected to one central switch by using coaxial, twisted-pair, or fiber-optic cables.
Logical topology
This central switch manages data transmission. Data that is sent from any node on the network must pass through the central switch to reach its destination. The central switch can also function as a repeater to prevent data loss.
3.	Mesh 
Physical topology
A mesh topology is a complex structure of connections that are similar to peer-to-peer, where the nodes are interconnected. Mesh networks can be full mesh or partial mesh. In a partial-mesh topology, all devices are connected to at least two other devices.
In a full-mesh topology, all nodes are interconnected. A full-mesh topology provides full redundancy for the network. It is an expensive topology because it requires each node to have multiple network adapters and cables. You will most likely find a full-mesh topology in a WAN.

4.	Hybrid topology
A hybrid topology combines two or more different topology structures. It is usually found in large organizations where separate departments have personalized network topologies to accommodate their network usage and other requirements. 
Today, the star-bus topology is the most common hybrid topology.
Network protocol defines the rules formatting and transmitting data between devices on a network. It typically operates at layer 3 (Network) or layer 4 (Transport) of the OSI model.
Network protocols fall int two categories:
!. Connection-oriented protocols
2. Connectionless protocol

IP addresses
An IP address uniquely identifies a device on a network. Each device on a network has an IP address, and it serves two main functions:
•	It identifies a host and a network. 
•	IP addresses are also used for location addressing.
IP addresses can be assigned to devices in a dynamic or static way. 
•	A device with a dynamic address has an assigned IP address that can change. This feature is useful in scenarios where devices might leave and come back to a network, like a work-assigned laptop that travels from the work network to the user's home network. 
•	A device with a static address has an IP address that does not change. This feature can be useful in many scenarios, such as servers or printers on a network that other devices often connect to.
IP addresses can also be made public or private:
•	A public IP address is an IP address that can be accessed over the internet. A public IP address is similar to a public phone number that is listed in a phone book or on the internet. The phone number is discoverable by anyone who wants to call it. A public IP address is a globally unique IP address that is assigned to a computing device that must access the internet.
•	A private IP address is assigned to computers within a private network and they cannot be accessed from the internet. Private addresses work well for use cases when an address is assigned to a device that you do not want other devices to know about. Returning to the phone number analogy, a private IP address would be similar to a private listing or a personal phone number that is not made publicly available. For example, the application and database servers in your data center are assigned private IP addresses because you might not want other devices to know about these servers.
When a network is assigned a range of IP addresses, such as 10.0.0.01–10.255.255.255, a few addresses have a special purpose. They are not assigned as host addresses. These addresses are the default router address and the broadcast address.
Example: Suppose the range of IP addresses is 10.0.0.0–10.255.255.255.
•	The default router address is typically the second address in the range: 10.0.0.1
o	The default router address is also known as the gateway address, and it is the IP address of the network router.
•	The broadcast address is the last address in the range: 10.255.255.255
o	The broadcast address is used to transmit messages to all devices that are connected to a network. If a message is sent to a broadcast address, then all nodes on the network can receive it. 


What is a subnet?
A subnet is network inside of a network. Subnetting is process of creating smaller networks by dividing a large block of addresses into several contiguous subdivisions. Subnets become useful when you must manage multiple networks. Organizations with multiple office locations can create individual subnets for their multiple locations.
Some important aspects of a subnet include these points:

•	A subnet creates multiple logical networks with different ranges of IP addresses. As an example, an organization could separate their networks. They could have an operational network and another network for machinery and IoT devices.

•	Classless Inter-Domain Routing (CIDR) notation is used to specify subnet IP address ranges. This system provides a shorthand for describing how the size of a network.

•	Devices that are in the same subnet can communicate with each other without using any routers.

•	Networks with Class A, B, or C IP addresses can be subnetted.

About IP address classes
An important aspect to understanding a network is understanding the record class that is associated with it. IP addresses are divided into classes based on their size and the subnetting capabilities of the network that they support. The potential for an organization to divide their network space is determined by the class of their IP addresses. Three of these classes are commonly used, and they provide a logical separation between the networks:
•	Class A  (0.0.0.0–127.255.255.255): Meant to be used for extremely large networks, like networks that are built by internet service providers (ISPs).
o	 A Class A record provides for up to 126 networks, which can each support up to 16,777,214 addresses! 
o	It is rare to see a single organization own a Class A record, but it does happen. Examples include Apple, who owns the entire 17.XXX.XXX.XXX space; and the Massachusetts Institute of Technology (MIT), who owns the 18.XXX.XXX.XXX domain.
•	Class B (128.0.0.0–191.255.255.255): Suitable for medium to large networks, for example, for enterprises and organizations. 
o	Class B records can  provide a capacity for up to 16, 384 networks,  accounting for approximately 65,000 addresses each.
•	Class C (192.0.0.0–233.255.255.255): Suitable for small networks, such as a home network or a  small business network.
o	Class C records provide 2,097,150 networks that can each allow for up to 254 addresses.
All networks—no matter what their size is—reserve some IP addresses for specific functions:
•	Unknown address (0.0.0.0): This address can have different meanings, depending on context. It might be used to represent an unknown or unroutable request, or it might be used to represent any address on a server. It virtually never refers to an individual device because it is not generally an assignable address.
•	Loopback (127.0.0.1): An address that returns a message back to its originating device. This address is used for testing and debugging purposes. It is also used to allow a specific configuration of inter-domain routing between network routers.
•	All devices – broadcast (255.255.255.255): An address that represents all devices that are connected to the network. The broadcast address is reserved so that information can be sent to every device on a network. It reduces the routing workload that would be incurred by individually routing information to each address.
It is useful to think about IP address classes when you consider subnetting. The IP address class provides a limit to how many networks can be created in that IP space. A very large organization might have a Class B record that enables them to create up to 16,382 networks, which can each support approximately 65,000 addresses. By using subnets, a network administrator might use this IP address to manage hundreds of individual networks across multiple cities, buildings, floors, and even departments.


Purpose of subnetting
Subnetting can be used to organize and optimize a network. For example, you can use subnets to:
•	Isolate different parts of the network

•	Apply different levels of security to different parts of the network

•	Relieve congestion on the network
Consider the following example:

•	A company has a network that connects two of its buildings, the Manufacturing building and the Warehouse building. The network was assigned the IP address range of 145.8.x.x. The company wants to create two separate subnets to provide a level of isolation between the devices in each building.
Default gateway is how a user access any other network.

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
Classless Inter-Domain Routing (CIDR) notation
The Classless Inter-Domain Routing (CIDR) format is used to specify IP address ranges when you create a network or a subnet.
The CIDR format specifies a block (which is known as a CIDR block) of IP addresses. This block is represented by using the format x.x.x.x/n, where:
•	x.x.x.x is an IP address. Recall that an IPv4 IP address is a 32-bit number that is represented as four numbers separated by dots (.). Thus, each x is an 8-bit number (a byte) that can have a value between 0–255. The IP address is logically divided into a network prefix and a host identifier. The network prefix identifies the network, and the host identifier identifies the host within the network.
•	/n specifies the length in bits of the network prefix portion of the IP address (starting from the leftmost bit). For an IPv4 IP address, the value of n can be from 0–32. The larger the value of n, the smaller the range size becomes, which results in a smaller number of usable IP addresses.

What is Amazon VPC?

Amazon Virtual Private Cloud (Amazon VPC) is a service that you can use to provision a logically isolated section of the AWS Cloud, which is called a virtual private cloud, or VPC. With a VPC, you can launch your AWS resources in a virtual network that you define. A VPC:

•	Enables you to create a private network in the AWS Cloud that uses many of the same concepts and constructs as an on-premises network
•	Gives you control over your virtual networking resources, including –

o	Selecting an IP address range
o	Creating subnets
o	Configuring route tables and network gateways
•	Enables you to customize its network configuration 
•	Enables you to use multiple layers of security

Using other AWS services with Amazon VPC 
•	Amazon VPC is an AWS foundational service and it works with many AWS services. For example, Amazon Elastic Compute Cloud (Amazon EC2) instances are deployed into a VPC. 
•	Understanding and implementing Amazon VPC will enable you to fully use other AWS services.

Amazon VPC is a foundational AWS service, and it works with many AWS services 

AWS OpsWork	Amazon DynamoDB		Amazon ElastiCache

Amazon EC2 Auto Scaling		Amazon RDS		Amazon EMR

Elasctic Load Balancing		Amazon WorkSpaces		AWS Data Pipeline

Amazon Simple Storage Services		AWS Elastic Beanstalk

Amazon VPC Features
•	A VPC:
o	Is dedicated to an AWS account
o	Belongs to a single AWS Region
o	Can span multiple Availability Zones
o	Is logically isolated from other VPCs

•	You can create multiple VPCs in an AWS account to separate networking environments
•	 You can create subnets in a VPC, though we recommend fewer subnets to reduce the complexity of the network topology
•	Multiple VPCs that span different Availability Zones in an AWS Region

IP addressing in Amazon VPC:
•	When you create a VPC, you must specify the IPv4 address range by choosing a CIDR block, such as 10.0.0.0/16. 
•	A VPC address range could be as large as /16(65,536 addresses) or as small as /28 (16 addresses).
•	 IP addresses should not overlap with the addresses of other networks that a VPC is connected to.

•	The address range of the VPC cannot be changed after the VPC is created.

Public subnet or private subnet
•	CIDR blocks define subnets.
•	AWS reserves the first four IP addresses and the last IP address of every subnet for internal networking purposes. 
•	A public subnet is accessible from within the VPC and from the internet.
•	A private subnet is only accessible from within the VPC, and it is not accessible from the internet.
•	When you create a VPC, you must specify the IPv4 address range by choosing a CIDR block, such as 10.0.0.0/16. 
•	A VPC address range could be as large as /16(65,536 addresses) or as small as /28 (16 addresses).
•	 IP addresses should not overlap with the addresses of other networks that a VPC is connected to.

•	The address range of the VPC cannot be changed after the VPC is created.

•	Amazon Virtual Private Cloud (Amazon VPC) is a service that you can use to build a custom-defined network in the AWS Cloud
•	The IP address range of a VPC is defined by using a CIDR block
•	You can create the following components in a VPC:

o	Public subnet or private subnet
o	Route table
o	Security group
o	Network access control list (network ACL)

Public subnet or private subnet

A subnet is a segment of a VPC address range. You can launch AWS services in a subnet.
•	CIDR blocks define subnets.
•	AWS reserves the first four IP addresses and the last IP address of every subnet for internal networking purposes. 
•	A public subnet is accessible from within the VPC and from the internet.
•	A private subnet is only accessible from within the VPC, and it is not accessible from the internet.
Route table

A route table contains a set of rules, called routes, that are used to determine where network traffic is directed. Each subnet in a VPC must be associated with a route table. The table controls the routing for the subnet. A subnet can only be associated with one route table, but you can associate multiple subnets with the same route table. 
To learn more about route tables, refer to Route tables in the AWS Documentation.

A security group is a virtual, stateful firewall that controls inbound and outbound network traffic to AWS resources and EC2 instances.
To learn more about security groups, refer to Security groups for your VPC in the AWS Documentation

Network access control list (network ACL) 

A network access control list (network ACL) is an optional layer of security for a VPC. It acts as a stateless firewall for controlling traffic in and out of one or more subnets. To learn more, refer to Network ACLs in the AWS Documentation.


Transmission Control Protocol (TCP) 
Recall that you first learned about TCP/IP earlier in this module. When Transmission Control Protocol (TCP) is combined with Internet Protocol (IP), they form the TCP/IP protocol suite, a set of protocols that the internet runs on. 
TCP/IP is a connection-oriented protocol. It defines how to establish and maintain network communications where application programs can exchange data. Data that is sent through this protocol is divided into smaller chunks called packets.
The goal of TCP/IP was to support an interconnection of networks, which was referred to as an internetwork, or internet. The internet comprises the groups of networks that communicate over this protocol. 

User Datagram Protocol (UDP)

The User Datagram Protocol (UDP) uses a simple, connectionless communication model to deliver data over an IP network. Compared to TCP, UDP only provides a minimum set of functions. It is considered to be unreliable because it does not guarantee the delivery or ordering of data. Its advantage is that it has a lower overhead, and it is faster than TCP.
UDP is used by applications that value speed over guaranteed delivery. Examples include video chat and video streaming. A missed packet might cause a short pause in the video, but the video will still be mostly understandable. However, if the users must wait for all the packets to be confirmed and ordered correctly, the delays can severely impact the quality of their experience.




Example of a URL


Secure Sockets Layer (SSL) and Transport Layer Security (TLS)
Secure Sockets Layer (SSL) is a standard for securing and safeguarding communications between two systems by using encryption.
Transport Layer Security (TLS) is an updated version of SSL that is more secure. Many security and standards organizations—such as the Payment Card Industry 
Security Standards Council (PCI SSC)—require organizations to use TLS version 1.2 to retain certification.

Remote Desktop Protocols (RDP and SSH)
•	Remote Desktop Protocol (RDP) is a protocol that is used to access the desktop of a remote Microsoft Windows computer. Use port 3389 with clients that are available for Microsoft Windows, Unix, Linux, macOS, and other operating systems.
•	Secure Shell Protocol (SSH) is a protocol that opens a secure command line interface (CLI) on a remote Linux or Unix computer.


Application protocol port numbers
Application protocols—such as Hypertext Transfer Protocol (HTTP) and File Transfer Protocol (FTP)—have assigned port numbers. 
These numbers are data endpoints. The ports provide devices with a way to understand what to do with the data that they receive. For example, a computer might download a file over FTP. The computer connects to the server and downloads the data over port 21. The computer will know how to handle that data because of the port that it used. The computer will thus be able to complete the download. 
The following table shows the network protocol and the port number that are used by common application protocols.
Application Protocol		Transport Protocol			Port Number
	HTTP					TCP					80
	HTTPS				TCP					443
	FTP					TCP					21
	SSH					TCP					22
	DNS	T				TCP					53																																																																																																																																																	Activity: ping and nslookup
 Open a Terminal window or a Command Prompt window, and complete the following steps:
1.	 Enter ping amazon.com
o	This command will return the IP address of the responding server.
o	You can view the additional connectivity information.
2.	Enter nslookup amazon.com
o	You can view the path that your computer takes to reach amazon.com.

Activity (Linux or macOS only): traceroute
Open a Terminal window or a Command Prompt window, and complete the following steps:
Enter traceroute amazon.com
•	You can observe how many hops the request took.
•	You can observe the latency of each hop.
•	If a hop lists an asterisk (*), it means that the hop timed ou


•	TCP and UDP are transport protocols. TCP is connection-oriented and UDP is connectionless.
•	Common application protocols that are used on the internet include HTTP, TLS/SSL, SMTP, and FTP.
•	Common network management and support protocols include DNS, DHCP, and ICMP.

•	Common utilities that are used to discover and troubleshoot network communication include ping, nslookup, and tracerout.


What is network security? 

Network security is a set of guidelines and configurations that are designed as preventative measures to protect the underlying networking infrastructure. Network security:

•	Is designed to preserve the usability and integrity of a network, and the data that flows through the network.
•	Is concerned with protecting a computer network and its resources from unauthorized access, misuse, modification, or destruction.
•	Combines policies and procedures with hardware and software solutions to achieve this goal.

The importance of network security 
According to the International Council of Electronic Commerce Consultants (EC-Council), "Information collected and stored electronically by the organizations is sensitive, crucial, and private information. It most likely includes crucial business data, customers’ personal information, and other information that is valuable for business transactions. Unauthorized access to the network and its data creates a threat to security. Several statutory privacy requirements should be followed like HIPAA, FEPRA, and others to prevent the data from unauthorized dissemination. Failure to do so will leave you responsible for the consequences."
For more information, refer to the How good is your Network Security? page on the EC-Council website.

•	Network security is concerned with the protection of a computer network and its resources from unauthorized access, misuse, modification, or destruction.

•	Types of network security threats include malware, social engineering, and network attacks.

•	Types of network security solutions include anti-malware, encryption, firewalls, and intrusion detection systems.

What is threat mitigation?
If your computing environment has been compromised or infected, you or your organization must take corrective actions to find and eliminate the threat. Corrective actions, such as prevention strategies or solutions, are put in place to combat or reduce IT threats on a computer, server, or network. 
Mitigation is a detection and protection policy that is adopted to safeguard networks.
Threat-mitigation methods
Mitigation methods include: 
•	Anti-malware – Malware detection 
•	Encryption
•	Authentication
•	Firewalls
•	IDS
•	Training
Penetration testing and vulnerability scanning are also essential.

Anti-malware
•	Anti-malware protects the device and the network. 
•	Malware is malicious computer software that is developed to act out malicious intentions. Malware is designed to damage computer hardware or steal data. Types of malware include viruses, worms, trojan horses, rootkits, ransomware, and keyloggers.
•	Malware detection examines networked devices and the data on those systems to detect malware. Malware-detection software is effective at detecting malware because it can involve the use of multiple mechanisms and methods. Types of malware-detection software include anti-virus software, anti-spyware, anti-spam, and firewalls.

Encryption
•	Encryption uses an algorithm to encrypt (or scramble) data.
•	A decryption key is needed to decrypt (or unscramble) the data.
•	Sensitive data that is at rest or in motion should be encrypted.

•	Data in motion versus data at rest 
•	Imagine that an email message is being sent. When the email message is sent from the first computer to the second computer, the data is in motion. After the email message reaches the second computer's inbox and is waiting to be opened, the data is at rest.

Encrypting data in motion and data at rest
Encrypting data at rest is vital for regulatory compliance. It helps ensure that sensitive data that is saved on disks is not readable by any user or application that does not have a valid key. Some compliance regulations—such as the Payment Card Industry Data Security Standard (PCI DSS) and the U.S. Health Insurance Portability and Accountability Act (HIPAA)—require the encryption of data at rest throughout the data lifecycle.

Certificate authentication and encryption

•	Digital certificates are electronic credentials that are used to represent the online identities of individuals, computers, and other entities on a network. Digital certificates are similar to personal ID cards.

•	A certificate with a public key and a corresponding private key can be used for encryption and decryption. When only the public key is used, the certificate establishes trust and performs encryption. 

•	There are two types of certificates—Certificates that are signed by a certificate authority (CA)and self-signed certificates.


•	Certificates that are signed by a certificate authority (CA) are signed by a third-party CA or a trusted CA.
•	Self-signed certificates are created, issued, and signed by the entities whose identities the certificates are meant to verify. 

A firewall is a network security device that helps to protect software, hardware, or web applications against common web exploits. These exploits might affect availability, compromise security, or consume excessive resources. Firewalls monitor incoming and outgoing network traffic. They allow data packets, or blocks data packets. Firewalls control how traffic reaches your applications by enabling you to create security rules that block common attack patterns, such as SQL injection or cross-site scripting. You can also create rules that filter out specific traffic patterns that you define.

Intrusion detection systems and intrusion prevention systems 
An intrusion detection system (IDS) is a combination of hardware and software that can detect network attacks and alert network information security professionals.
An IDS can discover an attack in a couple of ways:

•	An anomaly-based IDS examines baselines and deviations from baseline behavior. 
•	A signature-based IDS monitors for known patterns of attack. 
In addition, an IDS usually is either a network-based intrusion detection system (NIDS) or a host-based intrusion detection system (HIDS). A NIDS monitors for attacks on the network. Often, all the data that travels through the network also travels through the IDS for inspection and analysis. A NIDS is installed on a server and monitors logs and critical files on the server, monitoring for signs of a network attack.
An intrusion prevention system (IPS) is a network security tool that identifies and prevents threats. An IPS monitors networks for malicious incidents, and acts to prevent these malicious threats from affecting the system. IPSs are often behind the firewall, and they provide an extra layer of protection.

•	The goal of threat mitigation is to combat threats to an organization's data. It should be a proactive and preventive effort.

•	Anti-malware, encryption, certificate authentication, firewalls, IDSs, IPSs, and training are examples of effective threat-mitigation methods.


Wireless technologies
Wireless technologies are devices that communicate through the air.
•	Wireless technology plays a key role in today’s communications.
•	Emerging technologies—including robots, drones, self-driving vehicles, and new medical devices—all have a need for wireless technologies.

Examples of emerging wireless technologies
•	Wireless Gigabit (WiGig) was first announced in 2009 by the Wireless Gigabit Alliance.  WiGig was designed for fast speeds over short distances. You can take full advantage of a WiGig network if you have two or more devices on a WiGig network in the same room, with no obstacles between them. An example use case for WiGig is streaming content wirelessly from a device to a high-resolution TV.  
•	HaLow (pronounced halo) was first announced in 2016. It is a low-power, long-range version of Wi-Fi. HaLow was designed and developed for small data payloads and low-power devices. It can extend Wi-Fi to 900 MHz. It works well for sensors and wearable technologies, and it has twice the range of current Wi-Fi.
•	Bluetooth Low Energy (BLE) optimizes energy consumption. You might also hear Bluetooth Low Energy referred to as BLE, Bluetooth LE, or Bluetooth Smart. BLE technology is primarily used in mobile applications, and it is suitable for IoT. It was initially developed for the periodic transfer of small chunks of data over short ranges. BLE is used in solutions that span a range of domains, including healthcare, fitness, beacons, security, and home entertainment.
•	5G cellular systems are a new technology that has been deployed throughout 2019 and 2020. The complete rollout of this technology will take a couple of years. It will eventually provide download speeds up to 10 Gbps.

What is the Internet of Things (IoT)?
The Internet of Things (IoT) refers to physical devices, or things, that are connected to the internet so they can share and collect data.  
The primary goal of IoT is to enable devices to self-report in real time, which can improve efficiency. It can also surface important information more quickly than a system that depends on human intervention.
Many devices are in homes, factories, oil wells, hospitals, cars, and other places that need to be connected. Data from these devices can be collected, stored, and analyzed to design better solutions or products. IoT devices include consumer applications (like thermostats) and commercial applications (such as industrial sensors, smart watches, and smart toasters). They also include devices in the Internet of Medical Things (IoMT), such as health monitors.

Enterprise mobility
Enterprise mobility is a growing trend for businesses. This approach supports remote-working options, which use your personal laptops and mobile devices for business. Remote workers can connect and access data through cloud technology.
Two specific solutions enable enterprise mobility:

•	Bring your own device (BYOD) is the use of a personal device, like a mobile phone or tablet, on a public or private network. This solution includes the use of a personal device on a corporate network.
•	Mobile device management (MDM) is a term that describes the management of mobile devices, though it also applies to laptop and desktop computers. Organizations use MDM solutions so that they can provide devices with settings, software, and access to data in a secure way that complies with their needs.

What is IP?

IP is a network protocol that establishes the rules for relaying and routing data in the internet.
•	IP is a critical standard within the larger TCP/IP protocol suite when it is combined with the connection-oriented Transmission Control Protocol (TCP). TCP/IP implements the set of protocols that provides a crucial service for the internet because it enables the successful routing of network traffic among devices on a network. Some useful points about TCP/IP include that it:

•	Uses IP addresses to identify devices
•	Uses port numbers to identify endpoints

•	Supports subnetting to subdivide a network


IP addresses
An IP address uniquely identifies a device on a network. Each device on a network has an IP address, and it serves two main functions:
•	It identifies a host and a network. 
•	IP addresses are also used for location addressing.
IP addresses can be assigned to devices in a dynamic or static way. 
•	A device with a dynamic address has an assigned IP address that can change. This feature is useful in scenarios where devices might leave and come back to a network, like a work-assigned laptop that travels from the work network to the user's home network. 
•	A device with a static address has an IP address that does not change. This feature can be useful in many scenarios, such as servers or printers on a network that other devices often connect to.
IP addresses can also be made public or private:
•	A public IP address is an IP address that can be accessed over the internet. A public IP address is similar to a public phone number that is listed in a phone book or on the internet. The phone number is discoverable by anyone who wants to call it. A public IP address is a globally unique IP address that is assigned to a computing device that must access the internet.
•	A private IP address is assigned to computers within a private network and they cannot be accessed from the internet. Private addresses work well for use cases when an address is assigned to a device that you do not want other devices to know about. Returning to the phone number analogy, a private IP address would be similar to a private listing or a personal phone number that is not made publicly available. For example, the application and database servers in your data center are assigned private IP addresses because you might not want other devices to know about these servers.
When a network is assigned a range of IP addresses, such as 10.0.0.01–10.255.255.255, a few addresses have a special purpose. They are not assigned as host addresses. These addresses are the default router address and the broadcast address.
Example: Suppose the range of IP addresses is 10.0.0.0–10.255.255.255.
•	The default router address is typically the second address in the range: 10.0.0.1
o	The default router address is also known as the gateway address, and it is the IP address of the network router.
•	The broadcast address is the last address in the range: 10.255.255.255
o	The broadcast address is used to transmit messages to all devices that are connected to a network. If a message is sent to a broadcast address, then all nodes on the network can receive it. 

Converting an IP address into binary
An IP address consists of four numbers from 0 to 255 separated by a period, which is also known as a dotted quad (for example, 10.15.238.21). This format follows the IPv4 standard. It is important to note that the numbers in the IP address identify both the network and the device on the network.
To understand IP addressing, it is often better to convert the number to binary. A binary number is expressed in the base-2 numeral system, and it is consists of only zeroes and ones:
•	The value of 0 or 1 is known as a binary digit, or bit.
•	In an IPv4 address, each of the four numbers between the dots is an 8-bit binary number. Thus, the entire address is a 32-bit binary number.







