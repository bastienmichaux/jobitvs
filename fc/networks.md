> [Home](../README.md)

# Networks Questions

Content:
- [Fundamentals](#fundamentals)
- [Devices](#devices)
- [OSI Model](#osi)

## Fundamentals

<!-- $Q:C -->
<details id="network">
<summary><b>What is a computer network?</b></summary>

A computer network is a set of computers (and other electronical devices) connected to each other.

Conceptually, a network is made of **nodes**, **links** and has **edges**.

**Protocols** define how devices communicate.
</details>


<!-- $Q:D -->
<details id="node">
<summary><b>What is a network node?</b></summary>

All devices in a network are conceptual **nodes**.

A device where a connection takes place. A node can receive and send data from one endpoint to the other.

Nodes are connected to each other through **links**.

Two or more nodes are needed to form a network connection.
</details>


<!-- $Q:B -->
<details id="edge">
<summary><b>What is a network edge?</b></summary>
The network edge refers to the area where a device or local network interfaces with the internet. The edge is close to the devices it is communicating with and is the entry point to the network. The network edge is a crucial security boundary that network administrators must provide solutions for.
[Source](https://www.fortinet.com/resources/cyberglossary/network-edge)
</details>


<!-- $Q:D -->
<details id="link">
<summary><b>What is a network link?</b></summary>

the physical or logical connection between two or more nodes in a network. Link is the medium through which data is transmitted from one device to another. It is the basic building block of a network and is essential for communication between devices. Link can be wired or wireless, and can be used to connect computers, routers, switches, and other network devices.

[Source](https://www.alibabacloud.com/topic-center/network/ghcxip4b48-what-is-link-in-networking)
</details>


<!-- $Q:B -->
<details id="connection">
<summary><b>Define a network connection</b></summary>

Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection. Once a connection is established, data can be transferred between the applications running on each device.

Computers can be directly connected to each other, but most of the time computers will connect to a **router**.
</details>


## Devices

<!-- $Q:C -->
<details id="router">
<summary><b>What is a router?</b></summary>

A specialized computer that forwards **data packets** to the appropriate parts of a computer network.
</details>

<!-- What is a switch? -->
<!-- What is a firewall? -->


<!-- $Q:B -->
<details id="protocol">
<summary><b>What is a protocol and why use them?</b></summary>

A set of rules and standards that define how information is exchanged between devices and systems.

**Advantage of protocols:** they allow communication between devices and systems from different manufacturers/vendors. For example, a web browser developed by one company can communicate with a web server developed by another company, as long as they both adhere to the HTTP protocol.
</details>


<!-- $Q:C -->
<details id="packet">
<summary><b>What is a packet?</b></summary>

A block of data sent over a computer network.
</details>


<!-- $Q:C -->
<details id="segment">
<summary><b>What is a data segment?</b></summary>

Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.
<!-- $TODO segment size: -->
<!-- $TODO window size: -->
</details>


<!-- $Q:C -->
<details id="resource">
<summary><b>What is a network resource?</b></summary>

Anything (file, application) that can be found and used on a network.
</details>


<!-- $Q:C -->
<details id="port">
<summary><b>What is a port?</b></summary>

Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.

Some important ports:
- Port 80: HTTP
- Port 443: HTTPS
</details>


<!-- $Q:C -->
<details id="socket">
<summary><b>What is a socket?</b></summary>

A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.
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
<details id="osi-network">
<summary><b>Describe the OSI Network layer</b></summary>
It handles data routing, packet switching, and control of network congestion. Routers operate under this layer.
</details>

## References
- https://cs.fyi/guide/how-does-internet-work
