[Home](../README.md)

# Internet Questions

<!-- $Q:D -->
<details>
<summary>What is Internet?</summary>

A global network of computers connected to each other which communicate through a standardized set of protocols.

Internet is the best known Global Area Network (GAN), but the telephone and television networks are global too.
</details>


<!-- $Q:C -->
<details id="internet-vs-web">
<summary>What is the difference between Internet and the Web?</summary>

Internet is the infrastructure, whereas the Web is a service built on top of the infrastructure.

It is worth noting there are several other services built on top of the Internet, such as email and IRC.
</details>


<!-- $Q:B -->
<details id="history">
<summary>Resume the history of Internet</summary>

In the 60s, The US army needs a decentralized communication network in case of a nuclear attack. After developments by US universities and research centers, Internet opens to other countries (the UK first).

Internet relied on existing infrastructure (power, telephone) to develop itself.

**Modems** were developed to allow communication over telephone lines. By connecting routers to routers, networks to networks, Internet scaled worldwide.

**ISPs** opened the Internet to commercial use.
</details>


<!-- $Q:B -->
<details id="modem">
<summary>What is a modem?</summary>

A device that connects a computer network to the telephone infrastructure by modulating and demodulating (hence the name).

It modulates an analog signal to digital information.

It also decodes carrier signals to demodulates the transmitted information.

The main aim of the Modem is to produce a signal that can be transmitted easily and decoded to reproduce the digital data in its original form. Modems are also used for transmitting analog signals, such as Light Emitting Diodes (LED) or radio.
</details>


<!-- $Q:C -->
<details id="isp">
<summary>What is a ISP?</summary>

An Internet Service Provider is a company that manages some special routers that are all linked together and can also access other ISPs' routers. The Internet consists of this whole infrastructure of networks.
</details>


<!-- $Q:D -->
<details id="extranet-vs-intranet">
<summary>Difference between extranet and intranet?</summary>

Intranets: private networks, restricted to members of a particular organization.

Extranets: very similar to Intranets, except they open to other organizations. They're used to share information with clients and stakeholders.
</details>


<!-- $Q:D -->
<details id="ip">
<summary>What is IP?</summary>

The Internet Protocol.
</details>


<!-- $Q:B -->
<details id="ip-address">
<summary>What is an IP address?</summary>

A Internet Protocol Address is a unique identifier (UID) assigned to each device on a network. The IP Address is necessary to route data to the correct destination.

It's made of a series of numbers separated by dots (the dotted-decimal format), for example: `192.168.2.10`.

Note: the IP address is a logicial UID, while the MAC address is a physical UID.

IP addresses come in two versions:
1. the old **IPv4**
1. the more recent **IPv6**
</details>

<!-- 129) What are the important differences between MAC address and IP address
Here, are some difference between MAC and IP address:

MAC	IP address
The MAC address stands for Media Access Control Address.	IP address stands for Internet Protocol Address.
It consists of a 48-bit address.	It consists of a 32-bit address.
MAC address works at the link layer of the OSI model.	IP address works at the network layer of OSI model.
It is referred to as a physical address.	It is referred to as a logical address.
You can retrieve the MAC address of any device using ARP protocol.	You can retrieve the MAC address of any device RARP protocol.
Classes are not used in MAC address.	In IP, IPv4 uses A, B, C, D, and E classes. -->


<!-- What is IPv4? -->
<!-- What is IPv6?
IPv6, or Internet Protocol version 6, was developed to replace IPv4. At present, IPv4 is being used to control internet traffic but is expected to get saturated in the near future. IPv6 was designed to overcome this limitation. -->


<!-- $Q:C -->
<details id="domain-name">
<summary>What is a Domain Name?</summary>

Domain Name: a human-readable name (alias) used to identify an IP address.

E.g.: "google.com" is a domain name used on top of the IP address `142.250.190.78`. The IP address may change over time but the domain name can stay the same.

Domain names are translated into IP addresses using the **DNS**.
</details>


<!-- $Q:C -->
<details id="dns">
<summary>What is the DNS?</summary>

Domain Name System: part of the internet infrastructure, responsible for translating domain names into IP addresses. When you enter a domain name into your web browser, your computer sends a DNS query to a DNS server, which returns the corresponding IP address.

The main function of this network service is to provide host names to TCP/IP address resolution.
<!-- $TODO: what is a DNS query? -->
<!-- $TODO: what is a DNS server? -->
<!-- what is DNS address resolution ? -->
</details>


<!-- $Q:D -->
<details id="ssl-tls">
<summary>What is SSL/TLS?</summary>

Secure Sockets Layer/Transport Layer Security: provide secure communication over the internet.
</details>


<!-- $Q:D -->
<details id="ssl-tls-certificates">
<summary>What are SSL/TLS certificates?</summary>

SSL/TLS Certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted 3rd party (a Certificate Authority) to verify their authenticity.

Use SSL/TLS when transmitting sensitive data. Devs need to obtain and maintain valid SSL/TLS certificates for their servers, and follow best practices for configuring and securing SSL/TLS connections.

<!-- $TODO: certificate authority -->
</details>


<!-- $Q:D -->
<details id="#ssl-tls-handshakes">
<summary>What are SSL/TLS handshakes?</summary>

A process during which the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.
</details>


<!-- $Q:D -->
<details id="tcp">
<summary>What is TCP?</summary>

Transmission Control Protocol: communication protocol used by most internet-based applications (TCP/IP). Provides a reliable, ordered, and error-checked delivery of data.

<!-- TCP/IP is short for Transmission Control Protocol / Internet Protocol. This is a set of protocol layers that is designed to make data exchange possible on different types of computer networks, also known as a heterogeneous network. -->
</details>


<!-- $Q:D -->
<details id="http">
<summary>HTTP</summary>

Protocol used to transfer data between web clients and servers.

**How it works:** When you visit a website, your web browser sends an **HTTP request** to the server, asking for the webpage or other resource you've requested. The server then sends an **HTTP response** back to the client, containing the requested data.

By default, HTTP uses TCP port 80.
</details>


<!-- $Q:C -->
<details id="https">
<summary>What is HTTPS?</summary>

Hyper Text Transfer Protocol Secure: A more secure, encrypted version of HTTP. HTTPS encrypts the data using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption.

HTTPS by default uses port 443.
</details>


<!-- $Q:D -->
<details id="ftp">
<summary>What is FTP?</summary>

File Transfer Protocol.
</details>


<!-- $Q:D -->
<details id="smtp">
<summary>What is SMTP?</summary>

Simple Mail Transfer Protocol.
</details>


<!-- $Q:D -->
<details id="udp">
<summary>What is UDP?</summary>

User Datagram Protocol.
</details>

<!--  What is the difference between TCP and UDP?
Here are some major differences between TCP and UDP protocols:

TCP	UDP
It is a connection-oriented protocol.	It is a connectionless protocol.
TCP reads data as streams of bytes, and the message is transmitted to segment boundaries.	UDP messages contain packets that were sent one by one. It also checks for integrity at the arrival time.
TCP messages make their way across the Internet from one computer to another.	It is not connection-based, so one program can send lots of packets to another.
TCP rearranges data packets in the specific order.	UDP protocol has no fixed order because all packets are independent of each other.
The speed for TCP is slower.	UDP is faster as error recovery is not attempted.
Header size is 20 bytes	The header size is 8 bytes.
TCP is heavy-weight. TCP needs three packets to set up a socket connection before any user data can be sent.	UDP is lightweight. There are no tracking connections, ordering of messages, etc.
TCP does error checking and also makes error recovery.	UDP performs error checking, but it discards erroneous packets.
Acknowledgment segments	No Acknowledgment segments
Using handshake protocol like SYN, SYN-ACK, ACK	No handshake (so connectionless protocol)
TCP is reliable as it guarantees delivery of data to the destination router.	The delivery of data to the destination can’t be guaranteed in UDP.
TCP offers extensive error checking mechanisms because it provides flow control and acknowledgment of data.	UDP has just a single error checking mechanism that is used for checksums. -->

<!-- What is ICMP?
ICMP is an Internet Control Message Protocol. It provides messaging and communication for protocols within the TCP/IP stack. This is also the protocol that manages error messages that are used by network tools such as PING. -->

Sources:
- https://cs.fyi/guide/how-does-internet-work
- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work
- https://www.guru99.com/networking-interview-questions.html
