> [Home](../README.md)

# Internet Questions


<!-- $Q:C -->
<details id="internet-vs-web">
<summary><b>What is the difference between Internet and the Web?</b></summary>

Internet is the infrastructure, whereas the Web is a service built on top of the infrastructure.

It is worth noting there are several other services built on top of the Internet, such as email and IRC.
</details>


<!-- $Q:B -->
<details id="history">
<summary><b>Resume the history of Internet</b></summary>

In the 60s, The US army needs a decentralized communication network in case of a nuclear attack. After developments by US universities and research centers, Internet opens to other countries (the UK first).

Internet relied on existing infrastructure (power, telephone) to develop itself.

**Modems** were developed to allow communication over telephone lines. By connecting routers to routers, networks to networks, Internet scaled worldwide.

**ISPs** opened the Internet to commercial use.
</details>


<!-- $Q:B -->
<details id="modem">
<summary><b>What is a modem?</b></summary>

To connect our network to the telephone infrastructure, we need a special piece of equipment called a modem. This modem turns the information from our network into information manageable by the telephone infrastructure and vice versa.
</details>


<!-- $Q:C -->
<details id="isp">
<summary><b>What is a ISP?</b></summary>

An Internet Service Provider is a company that manages some special routers that are all linked together and can also access other ISPs' routers. The Internet consists of this whole infrastructure of networks.
</details>


<!-- $Q:D -->
<details id="extranet-vs-intranet">
<summary><b>Difference between extranet and intranet?</b></summary>

Intranets: private networks, restricted to members of a particular organization.

Extranets: very similar to Intranets, except they open to other organizations. They're used to share information with clients and stakeholders.
</details>


<!-- $Q:D -->
<details id="ip">
<summary><b>What is IP?</b></summary>

Internet protocol
</details>


<!-- $Q:C -->
<details id="ip-address">
<summary><b>What is an IP address?</b></summary>

IP Address: A unique identifier assigned to each device on a network. Necessary to route data to the correct destination. 

It's an address typically made of a series of four numbers separated by dots, for example: `192.168.2.10`.

There are two versions of IP addresses: the old **IPv4** and the more recent **IPv6**.
</details>


<!-- $Q:C -->
<details id="domain-name">
<summary><b>What is a Domain Name?</b></summary>

Domain Name: a human-readable name (alias) used to identify an IP address.

E.g.: "google.com" is a domain name used on top of the IP address `142.250.190.78`. The IP address may change over time but the domain name can stay the same.

Domain names are translated into IP addresses using the **DNS**.
</details>


<!-- $Q:C -->
<details id="dns">
<summary><b>What is the DNS?</b></summary>

Domain Name System: part of the internet infrastructure, responsible for translating domain names into IP addresses. When you enter a domain name into your web browser, your computer sends a DNS query to a DNS server, which returns the corresponding IP address.
<!-- $TODO: what is a DNS query? -->
<!-- $TODO: what is a DNS server? -->
</details>


<!-- $Q:D -->
<details id="ssl-tls">
<summary><b>What is SSL/TLS?</b></summary>

Secure Sockets Layer/Transport Layer Security: provide secure communication over the internet.
</details>


<!-- $Q:D -->
<details id="ssl-tls-certificates">
<summary><b>What are SSL/TLS certificates?</b></summary>

SSL/TLS Certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted 3rd party (a Certificate Authority) to verify their authenticity.

Use SSL/TLS when transmitting sensitive data. Devs need to obtain and maintain valid SSL/TLS certificates for their servers, and follow best practices for configuring and securing SSL/TLS connections.

<!-- $TODO: certificate authority -->
</details>


<!-- $Q:D -->
<details id="#ssl-tls-handshakes">
<summary><b>What are SSL/TLS handshakes?</b></summary>

A process during which the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.
</details>


<!-- $Q:D -->
<details id="tcp">
<summary><b>What is TCP?</b></summary>

Transmission Control Protocol: communication protocol used by most internet-based applications (TCP/IP). Provides a reliable, ordered, and error-checked delivery of data.
</details>


<!-- $Q:D -->
<details id="http">
<summary><b>HTTP</b></summary>

Protocol used to transfer data between web clients and servers.

**How it works:** When you visit a website, your web browser sends an **HTTP request** to the server, asking for the webpage or other resource you've requested. The server then sends an **HTTP response** back to the client, containing the requested data.

By default, HTTP uses TCP port 80.
</details>


<!-- $Q:C -->
<details id="https">
<summary><b>What is HTTPS?</b></summary>

Hyper Text Transfer Protocol Secure: A more secure, encrypted version of HTTP. HTTPS encrypts the data using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption.

HTTPS by default uses port 443.
</details>


<!-- $Q:D -->
<details id="ftp">
<summary><b>What is FTP?</b></summary>

File Transfer Protocol.
</details>


<!-- $Q:D -->
<details id="smtp">
<summary><b>What is SMTP?</b></summary>

Simple Mail Transfer Protocol.
</details>


<!-- $Q:D -->
<details id="udp">
<summary><b>What is UDP?</b></summary>

User Datagram Protocol.
</details>


Sources:
- https://cs.fyi/guide/how-does-internet-work
- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work
