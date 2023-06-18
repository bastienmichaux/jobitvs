[Home](../README.md)

# Networks Questions

Content:
- [Fundamentals](#fundamentals)
- [Devices](#devices)
- [Topology](#topology)
- [OSI Model](#osi)

## Fundamentals

<!-- Here's a bullet-point list outlining the conceptual parts of a computer network and how they relate to each other:

Nodes: Devices or network elements within the network infrastructure, such as routers, switches, hubs, bridges, or endpoints, that facilitate the transmission and routing of data.
Links: Physical or logical connections that enable the transfer of data between nodes, which can be wired (e.g., Ethernet cables) or wireless (e.g., Wi-Fi).
Protocols: Rules and procedures that govern the communication and interaction between devices within the network, ensuring compatibility and standardization. Examples include TCP/IP, HTTP, and Ethernet.
Topology: The arrangement or structure of the network, defining how nodes and links are interconnected. Common topologies include bus, star, ring, and mesh.
Network Services: Services and applications that utilize the network infrastructure to enable functions such as file sharing, email, web browsing, and video conferencing.
Network Layers: Hierarchical levels or abstraction of network functionality, often represented using a layered model like the OSI (Open Systems Interconnection) or TCP/IP model, with each layer responsible for specific tasks and protocols.
Network Addressing: The assignment of unique addresses to devices within the network, such as IP addresses, which allow for identification and communication between devices.
Security: Measures and protocols implemented to protect the network and its data from unauthorized access, threats, and vulnerabilities, including firewalls, encryption, authentication, and access control.
These conceptual parts work together to establish and maintain computer networks, enabling communication, data transfer, and the delivery of network services. The nodes and links form the network infrastructure, while protocols and addressing govern communication. The network topology defines the physical or logical arrangement, and network services utilize the network to provide functionality. Network layers provide structure and organization, and security ensures the integrity and confidentiality of network communications. -->

<!-- $Q:C -->
<details id="network">
<summary>What is a computer network?</summary>

A computer network is a set of computers (and other electronical devices) connected together so they can share and exchange information.

Networking requires **electronic connections**; connections can be wired (ethernet cables) or wireless (Wi-Fi, Bluetooth).

Conceptually, a network is made of **nodes** connected together by **links**.

Its borders are called **network edges**.

**Protocols** define how devices communicate and share data.

<!-- **Networking** is a set of processes that interconnect and administrate network devices. -->

<!-- Computer networks can be physical or logical. A physical computer network is a real network comprised of the cable and devices that send data back and forth. Logical networks are software representations of a physical network. They are built on top of a physical network. -->
</details>




<!-- $Q:D -->
<details id="node">
<summary>What is a network node?</summary>

A node is any device connected to a computer network.
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
<summary>What is a network edge?</summary>

The network edge is the area where a device or local network interfaces with the internet. The edge is close to the devices it is communicating with and is the entry point to the network. The network edge is a crucial security boundary that network administrators must provide solutions for.

is where your network meets the outside world. It includes devices like modems and routers. It's like the "border" of your network, where the internal devices meet the external network infrastructure.

The network edge is important because it's where we have to protect our devices from potential threats that might come from the outside.
</details>


<!-- $Q:B -->
<details id="connection">
<summary>What is a network connection?</summary>

Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the  devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection. Once a connection is established, data can be transferred between the applications running on each device.

Computers can be directly connected to each other, but most of the time computers will connect to a **router**.
</details>


<!-- What is an endpoint?
the origin or destination of data within the network
 -->

<!-- What is the difference between an endpoint and a node?
Endpoint: An endpoint refers to a specific device or computer that is connected to a network. It represents the origin or destination of data within the network. Endpoints are typically associated with the network edge, and they can include devices such as computers, smartphones, servers, or any device that connects to the network.

Node: A node, on the other hand, is a broader term that encompasses any device or network element within a computer network. It refers to any point of connection within the network infrastructure. Nodes can include routers, switches, hubs, bridges, and other network devices that facilitate the transmission and routing of data. Nodes are responsible for forwarding and directing data packets to their intended destinations.

an endpoint is a specific device or computer that connects to a network and represents the starting or ending point of data transmission, often associated with the network edge. A node, on the other hand, is a more general term that refers to any device or network element within the network infrastructure that facilitates the flow of data. Nodes include both endpoint devices and network devices like routers and switches.
 -->

<!-- $Q:B -->
<details id="protocol">
<summary>What is a protocol and why use them?</summary>

A set of rules and standards that define how information is exchanged between devices and systems.

**Advantage of protocols:** they allow communication between devices and systems from different manufacturers/vendors. For example, a web browser developed by one company can communicate with a web server developed by another company, as long as they both adhere to the HTTP protocol.
</details>


<!-- What are the important elements of the protocol?
Here, are three most important elements of the protocol:

Syntax: It is the format of the data. It is an order the data is displayed.
Semantics: It describes the meaning of the bits in each section.
Timing: What time the data is to be sent and how fast it is to be sent. -->


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
<details id="resource">
<summary>What is a network resource?</summary>

Anything (file, application) that can be found and used on a network.
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


## Devices


## Topology


## OSI Model


## References
- https://chat.openai.com/
- https://cs.fyi/guide/how-does-internet-work
- https://www.guru99.com/networking-interview-questions.html
- https://www.fortinet.com
