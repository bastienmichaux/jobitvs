[Home](../README.md)

# Networks Questions

Content:
- [Fundamentals](#fundamentals)
- [Devices](#devices)
- [Topology](#topology)
- [Connections](#connections)
- [OSI Model](#osi)





## Fundamentals

<!-- $Q:C -->
<details id="network">
<summary>What is a computer network?</summary>

A computer network is a set of computers (and other electronical devices) connected together so they can share and exchange information. **Protocols** define how devices communicate and share data.

Computer networks can be physical or logical:
- A physical network is made of physical devices and cables.
- Logical networks are software representations of a physical network. They are built on top of a physical network.

Conceptually, a network is made of **nodes** connected together by **links**. Its borders/limits are called **edges**.
</details>




<!-- $Q:C -->
<details>
<summary>What are the conceptual parts of computer networking?</summary>

1. **Nodes:** Devices or network elements that transmit data.
1. **Links:** Physical or logical connections that enable the transfer of data between nodes. They can be wired (e.g., Ethernet cables) or wireless (e.g., Wi-Fi).
1. **Protocols:** Rules and procedures that govern the communication and interaction between devices. Examples include TCP/IP, HTTP, and Ethernet.
1. **Topology:** The arrangement or structure of the network, defining how nodes and links are interconnected. Common topologies include bus, star, ring, and mesh.
1. **Network Services:** Services and applications that utilize the network infrastructure to enable functions such as file sharing, email, web browsing, and video conferencing.
1. **Network Layers:** Hierarchical levels or abstraction of network functionality, often represented using a layered model like the OSI (Open Systems Interconnection) or TCP/IP model, with each layer responsible for specific tasks and protocols.
1. **Network Addressing:** The assignment of unique addresses to devices within the network, such as IP addresses, which allow for identification and communication between devices.
1. **Security:** Measures and protocols implemented to protect the network and its data. Security measures include firewalls, encryption, authentication, or access control.

The nodes and links form the network infrastructure, while protocols and addressing govern communication.

The network topology defines the physical or logical arrangement, and network services utilize the network to provide functionality. Network layers provide structure and organization, and security ensures the integrity and confidentiality of network communications.
</details>




<!-- $Q:D -->
<details>
<summary>What is an endpoint?</summary>

A node is an endpoint if it is an origin or destination of data within the network. This excludes devices that only transmit data.
</details>




<!-- $Q:D -->
<details id="node">
<summary>What is a network node?</summary>

A node is any device connected to a computer network. An endpoint is a node.
</details>




<!-- $Q:B -->
<details>
<summary>What is the difference between an endpoint and a node?</summary>

All endpoints are nodes, but not all nodes are endpoints.

Endpoint:
- It represents the origin or destination of data within the network.
- Endpoints are typically associated with the network edge (access to the Internet)
- they can include devices such as computers, smartphones, servers, or any device that connects to the network
- typically doesn't include network devices such as routers, switches, hubs, bridges...

Node:
- any device or network element within a computer network, including endpoints
- refers to any point of connection within the network infrastructure
- can include routers, switches, hubs, bridges, and other network devices that facilitate the transmission and routing of data, but aren't generally considered endpoints
- nodes are responsible for forwarding and directing data packets to their intended destinations (the endpoints)
</details>




<!-- $Q:D -->
<details id="link">
<summary>What is a network link?</summary>

A network link is a connection between two or more nodes (such as a ethernet cable or Wi-Fi).

Link can be wired or wireless, physical or logical.

[Source](https://www.alibabacloud.com/topic-center/network/ghcxip4b48-what-is-link-in-networking)
</details>




<!-- $Q:B -->
<details id="edge">
<summary>What is the network edge?</summary>

The network edge is the area where a device or local network interfaces with the internet. The edge is close to the devices it is communicating with and is the entry point to the network. The network edge is a crucial security boundary that network administrators must provide solutions for.

is where your network meets the outside world. It includes devices like modems and routers. It's like the "border" of your network, where the internal devices meet the external network infrastructure.

The network edge is important because it's where we have to protect our devices from potential threats that might come from the outside.
</details>




<!-- $Q:B -->
<details id="protocol">
<summary>What are protocols and why use them?</summary>

A protocol is a set of rules and standards that define how information is exchanged between devices.

Protocols are necessary to allow communication between devices and systems from different manufacturers/vendors. For example, a web browser developed by one company can communicate with a web server developed by another company, as long as they both adhere to the HTTP protocol.
<blockquote>

  <!-- $Q:D -->
  <details>
  <summary>What are the important elements of the protocol?</summary>
  
  A protocol has 3 main elements:
  - Syntax: It is the format of the data. It is an order the data is displayed.
  - Semantics: It describes the meaning of the bits in each section.
  - Timing: What time the data is to be sent and how fast it is to be sent.
  </details>
</blockquote>
</details>




<!-- $Q:D -->
<details id="resource">
<summary>What is a network resource?</summary>

Anything (file, application) that can be found and used on a network.
</details>




## Devices

<!-- $Q:D -->
<details id="devices-examples">
<summary><b>Give examples of some network devices</b></summary>

A computer network use specialized devices and computers such as:
- router
- switch
- firewall
- hub
- bridge
<!-- - adapter -->
<!-- - concentrator -->
<!-- - repeater -->
</details>




<!-- $Q:C -->
<details id="router">
<summary><b>What is a router?</b></summary>

A network device that routes **data packets** to the appropriate parts of a computer network. Routers operate at the OSI Network Layer.

They connect network segments (aka subnets) together. They store information (such as paths, hops, and bottlenecks) in routing tables to determine the best path for data transfer.
</details>




<!-- $Q:D -->
<details>
<summary>How do you manage a network using a router?</summary>

Routers have a built-in console for configuring the network, e.g.:
- data logging
- available/restricted resources
- access times (day/night, etc)
- available/restricted websites
</details>




<!-- $Q:D -->
<details>
<summary>What is the difference between a hub and a switch?</summary>

Here is the major difference between Hub and switch:
1. OSI layer:
  - A hub operates on the physical layer
  - A switch operates on the data link layer
1. Passive/active:
  - a Hub is a passive device
  - a switch is an active device
1. MAC addresses:
  - A network hub can’t store MAC addresses
1. Transmission mode:
  - hub: Half-duplex
  - switch: Full duplex
1. software:
  - hub: Does not use software / dumb device
  - switch: Has software for administration / smart device
</details>




## Connections

<!-- $Q:C -->
<details id="packet">
<summary>What is a packet?</summary>

A block of data sent over a computer network.
</details>




<!-- $Q:C -->
<details id="segment">
<summary>What is a data segment?</summary>

Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.
<!-- $TODO segment size: -->
<!-- $TODO window size: -->
</details>




<!-- $Q:C -->
<details id="port">
<summary>What is a port?</summary>

Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.

Some important ports:
- Port 80: HTTP
- Port 443: HTTPS
</details>




<!-- $Q:C -->
<details id="socket">
<summary>What is a socket?</summary>

A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.
</details>




<!-- $Q:B -->
<details id="connection">
<summary>What is a network connection?</summary>

Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the  devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection. Once a connection is established, data can be transferred between the applications running on each device.

Computers can be directly connected to each other, but most of the time computers will connect to a **router**.
</details>




## Topology

<!-- $Q:D -->
<details>
<summary>What is Network Topology?</summary>

Network Topology refers to the layout of a computer network (physical or logical).

The physical layout shows how devices and cables are laid out and connected.
</details>




<!-- $Q:D -->
<details>
<summary>What is a LAN?</summary>

Local Area Network: a computer network located within a small physical location (usually, a single building or building floor).
</details>




<!-- $Q:D -->
<details>
<summary>What is the difference between Active and Passive Topology?</summary>
When the computers on the network simply listen and receive the signal, they are referred to as passive because they don't amplify the signal in any way.
</details>




<!-- $Q:D -->
<details>
<summary>What is a point to point link?</summary>
A direct connection between two computers on a network. A point to point connection does not need any other network devices other than connecting a cable to the NIC cards of both computers.
</details>




<!-- $Q:D -->
<details>
<summary>What is star topology?</summary>

Star topology consists of a central hub that connects to nodes. This is one of the easiest to set up and maintain.

<blockquote>
  <!-- $Q:D -->
  <details>
  <summary>Pros/cons of star topology?</summary>

  Pros:
  - Easy to troubleshoot, set up, and modify
  - Failure on one node won't affect other nodes
  - Fast performance with few nodes and very low network traffic
  - adding, deleting, moving devices is easy

  Cons:
  - If the Hub or concentrator fails, the entire network becomes unusable
  - Expensive to install
  - Heavy network traffic can sometimes slow the bus considerably.
  - Performance depends on the Hub’s capacity
  <!-- - A damaged cable or lack of proper termination may bring the network down -->
  </details>
</blockquote>
</details>




## OSI Model

<!-- $Q:D -->
<details id="osi">
<summary><b>What is the OSI model?</b></summary>

Open Systems Interconnect: serves as a reference model for data communication. It is made up of 7 layers:
1. Physical
1. Data Link
1. Network
1. Transport
1. Session
1. Presentation
1. Application

Each OSI layer defines a particular aspect of how network devices connect and communicate with one another. Each layer depends on those below (all depend on the 1st, physical one).
</details>




<!-- $Q:D -->
<details>
<summary>Why the standard OSI model is known as 802.xx?</summary>

The OSI model was started in February 1980. In 802.XX, "80" stands for the year 1980, and "2" represents the month of February.
</details>




<!-- $Q:D -->
<details id="">
<summary><b>Describe the OSI Physical Layer</b></summary>
The Physical Layer does the conversion from data bits to the electrical signal, and vice versa. This is where network devices and cable types are considered and setup.
</details>




<!-- $Q:D -->
<details id="osi-network">
<summary><b>Describe the OSI Network Layer</b></summary>

The Network Layer handles data routing, packet switching, and control of network congestion. Routers operate under this layer.
</details>




<!-- $Q:D -->
<details id="">
<summary><b>Describe the OSI Session Layer</b></summary>

The Session Layer provides the protocols and means for two devices on the network to communicate with each other by holding a session. This includes setting up the session, managing information exchange during the session, and tear-down process upon termination of the session.
</details>




## References
- https://chat.openai.com/
- https://cs.fyi/guide/how-does-internet-work
- https://www.fortinet.com
- https://www.guru99.com/networking-interview-questions.html
- https://www.ibm.com/docs/en/iis/9.1?topic=topologies-active-passive-topology
