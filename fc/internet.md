> [Home](../README.md)

# Internet Questions

Questions:
- [What is the difference between Internet and the Web?](#internet-vs-web)
- [Resume the history of Internet](#history)
- [What is a modem?](#modem)
- [What is a ISP?](#isp)
- [Difference between extranet and intranet?](#extranet-vs-intranet)
- [What is IP?](#ip)
- [What is an IP address?](#ip-address)
- [What is a Domain Name?](#domain-name)
- [What is the DNS?](#dns)
- [What is SSL/TLS?](#ssl-tls)
- [What are SSL/TLS certificates?](#ssl-tls-certificates)
- [What are SSL/TLS handshakes?](#ssl-tls-handshakes)
- [](#)
<!-- - [TCP](#tcp)
- [HTTP](#http)
- [HTTPS](#https)
- [FTP](#ftp)
- [SMTP](#smtp)
- [UDP](#udp) -->

<!-- $Q:C -->
<details id="internet-vs-web">
<summary><b>What is the difference between Internet and the Web?</b></summary>
<blockquote>

Internet is the infrastructure, whereas the Web is a service built on top of the infrastructure.

It is worth noting there are several other services built on top of the Internet, such as email and IRC.
</blockquote></details>


<!-- $Q:B -->
<details id="history">
<summary><b>Resume the history of Internet</b></summary>
<blockquote>

In the 60s, The US army needs a decentralized communication network in case of a nuclear attack. After developments by US universities and research centers, Internet opens to other countries (UK first).

Internet relied on existing infrastructure (power, telephone) to develop itself. **Modems** were developed to allow communication over telephone lines. By connecting routers to routers, networks to networks, Internet scaled worldwide.
</blockquote></details>


<!-- $Q:D -->
<details id="isp">
<summary><b>What is a ISP?</b></summary>
<blockquote>

An Internet Service Provider is a company that manages some special routers that are all linked together and can also access other ISPs' routers. The Internet consists of this whole infrastructure of networks.
</blockquote></details>


<!-- $Q:B -->
<details id="modem">
<summary><b>What is a modem?</b></summary>
<blockquote>

To connect our network to the telephone infrastructure, we need a special piece of equipment called a modem. This modem turns the information from our network into information manageable by the telephone infrastructure and vice versa.
</blockquote></details>


<!-- $Q:D -->
<details id="extranet-vs-intranet">
<summary><b>Difference between extranet and intranet?</b></summary>
<blockquote>

Intranets: private networks, restricted to members of a particular organization.

Extranets are very similar to Intranets, except they open all (or part) of a private network to other organizations. They're used to share information with clients and stakeholders.
</blockquote></details>


<!-- $Q:D -->
<details id="ip">
<summary><b>What is IP?</b></summary>
<blockquote>

Internet protocol
</blockquote></details>


<!-- $Q:C -->
<details id="ip-address">
<summary><b>What is an IP address?</b></summary>
<blockquote>

IP Address: A unique identifier assigned to each device on a network. Necessary to route data to the correct destination. 

It's an address typically made of a series of four numbers separated by dots, for example: `192.168.2.10`.

There are two versions of IP addresses: the old **IPv4** and the more recent **IPv6**.
</blockquote></details>


<!-- $Q:C -->
<details id="domain-name">
<summary><b>What is a Domain Name?</b></summary>
<blockquote>

Domain Name: a human-readable name (alias) used to identify an IP address.

E.g.: "google.com" is a domain name used on top of the IP address `142.250.190.78` (but this address may change over time).

Domain names are translated into IP addresses using the Domain Name System (**DNS**).
</blockquote></details>


<!-- $Q:C -->
<details id="dns">
<summary><b>What is the DNS?</b></summary>
<blockquote>

Domain Name System (DNS): part of the internet infrastructure, responsible for translating domain names into IP addresses. When you enter a domain name into your web browser, your computer sends a DNS query to a DNS server, which returns the corresponding IP address.
</blockquote></details>


<!-- $Q:D -->
<details id="ssl-tls">
<summary><b>What is SSL/TLS?</b></summary>
<blockquote>

SSL/TLS: Secure Sockets Layer/Transport Layer Security: provide secure communication over the internet.
</blockquote></details>


<!-- $Q:D -->
<details id="ssl-tls-certificates">
<summary><b>What are SSL/TLS certificates?</b></summary>
<blockquote>

SSL/TLS Certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted third party (a Certificate Authority) to verify their authenticity.

Use SSL/TLS when transmitting sensitive data. Devs need to obtain and maintain valid SSL/TLS certificates for their servers, and follow best practices for configuring and securing SSL/TLS connections.
</blockquote></details>


<!-- $Q:D -->
<details id="#ssl-tls-handshakes">
<summary><b>What are SSL/TLS handshakes?</b></summary>
<blockquote>

Handshake: During the SSL/TLS handshake process, the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.
</blockquote></details>


<!-- $Q:D -->
<details id="tcp">
<summary><b>What is TCP?</b></summary>
<blockquote>

Transmission Control Protocol: communication protocol used by most internet-based applications (TCP/IP). Provides a reliable, ordered, and error-checked delivery of data.
</blockquote></details>


<!-- $Q:D -->
<details id="http">
<summary><b>HTTP</b></summary>
<blockquote>

Protocol used to transfer data between web clients and servers.

How it works: When you visit a website, your web browser sends an **HTTP request** to the server, asking for the webpage or other resource you've requested. The server then sends an **HTTP response** back to the client, containing the requested data.

By default, HTTP uses TCP port 80.
</blockquote></details>


<!-- $Q:C -->
<details id="https">
<summary><b>What is HTTPS?</b></summary>
<blockquote>

Hyper Text Transfer Protocol Secure: A more secure, encrypted version of HTTP. HTTPS encrypts the data using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption.

HTTPS by default uses port 443.
</blockquote></details>


<!-- $Q:D -->
<details id="ftp">
<summary><b>What is FTP?</b></summary>
<blockquote>

File Transfer Protocol 
</blockquote></details>


<!-- $Q:D -->
<details id="smtp">
<summary><b>What is SMTP?</b></summary>
<blockquote>

Simple Mail Transfer Protocol
</blockquote></details>


<!-- $Q:D -->
<details id="udp">
<summary><b>What is UDP?</b></summary>
<blockquote>

User Datagram Protocol
</blockquote></details>


Sources:
- https://cs.fyi/guide/how-does-internet-work
- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work
