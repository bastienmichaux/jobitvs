[Home](../README.md)

# Internet Questions

<!-- $Q:D -->
<details>
<summary>What is Internet?</summary>

A global network of computers (GAN) connected to each other which communicate through a set of standardized protocols. The core of the internet is a global network of interconnected routers.

Roughly speaking, Internet is a network of networks. Data is broken up into small packets that are sent from your device to a series of routers until the packet reaches its final destination.
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




## Protocols

<!-- $Q:D -->
<details>
<summary>What are the main Internet protocols?</summary>

IP is responsible for routing packets of data to their correct destination.

TCP and UDP ensure that packets are transmitted reliably and efficiently.

DNS is used to translate domain names into IP addresses.

HTTP and HTTPS are used to transfer data between clients and servers.
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

<blockquote>
  <!-- $Q:D -->
  <details>
  <summary>What is a private IP address?</summary>
  Private IP addresses are assigned for use on intranets. These addresses are used for internal networks and are not routable on external public networks. These ensure that no conflicts are present among internal networks. At the same time, the same range of private IP addresses is reusable for multiple intranets since they do not “see” each other.
  </details>
</blockquote>
</details>




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




Sources:
- https://cs.fyi/guide/how-does-internet-work
- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work
- https://www.guru99.com/networking-interview-questions.html
