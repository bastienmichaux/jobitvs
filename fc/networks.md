> [Home](../README.md)

# Networks Questions


<!-- $Q:C -->
<details id="network">
<summary><b>What is a computer network?</b></summary>
<blockquote>

A computer network is a set of computers (and other electronical devices) connected to each other. Computers can be directly connected to each other, but most of the time computers will connect to a **router**. **Protocols** define how devices communicate.
</blockquote></details>


<!-- $Q:B -->
<details id="protocol">
<summary><b>What is a protocol and why use them?</b></summary>
<blockquote>
A set of rules and standards that define how information is exchanged between devices and systems.

**Advantage of protocols:** they allow communication between devices and systems from different manufacturers/vendors. For example, a web browser developed by one company can communicate with a web server developed by another company, as long as they both adhere to the HTTP protocol.
</blockquote></details>


<!-- $Q:C -->
<details id="router">
<summary><b>What is a router?</b></summary>
<blockquote>

A specialized computer that forwards data packets to the appropriate parts of a computer network.
</blockquote></details>


<!-- $Q:C -->
<details id="packet">
<summary><b>What is a packet?</b></summary>
<blockquote>

A block of data sent over a computer network.
</blockquote></details>


<!-- $Q:C -->
<details id="segment">
<summary><b>What is a data segment?</b></summary>
<blockquote>

Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.
<!-- $TODO segment size: -->
<!-- $TODO window size: -->
</blockquote>
</details>


<!-- $Q:C -->
<details id="resource">
<summary><b>What is a network resource?</b></summary>
<blockquote>

Anything (file, application) that can be found and used on a network.
</blockquote></details>


<!-- $Q:C -->
<details id="port">
<summary><b>What is a port?</b></summary>
<blockquote>

Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.

Some important ports:
- Port 80: HTTP
- Port 443: HTTPS
</blockquote>
</details>


<!-- $Q:X -->
<details id="socket">
<summary><b>What is a socket?</b></summary>
<blockquote>

A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.
</blockquote>
</details>


<!-- $Q:B -->
<details id="connection">
<summary><b>Define a network connection</b></summary>
<blockquote>

Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection. Once a connection is established, data can be transferred between the applications running on each device.
</blockquote>
</details>

Sources:
- https://cs.fyi/guide/how-does-internet-work
