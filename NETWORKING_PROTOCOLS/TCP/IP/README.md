# TCP / IP

- TCP/IP stands for Transmission Control Protocol/Internet Protocol.
- TCP protocol is a 3way handshake model.
- connection is established before sending packets.
- It's a suite of communication protocols used to interconnect network devices on the internet. 
- TCP/IP is also used as a communications protocol in a private computer network


## Layers of TCP/IP Protocol: 

**1. Network Interface Layer (Link Layer)**
**- Internetwork Layer**
**- Network access Layer**

*Description:*
The Network Interface Layer is responsible for the physical transmission of data on the network. It includes hardware devices like Ethernet and Wi-Fi, and protocols that control the hardware.

*Functions:*
- Defines how data is physically sent through the network.
- Handles framing, addressing, and error detection.

*Protocols:*
- Ethernet
- Wi-Fi (IEEE 802.11)
- ARP (Address Resolution Protocol)
- NDP (Neighbor Discovery Protocol for IPv6)


**2. Internet Layer**

*Description:*
The Internet Layer manages the logical addressing and routing of data packets across different networks. It ensures that packets are sent from the source to the destination correctly.

*Functions:*
- Packet forwarding and routing.
- Logical addressing (IP addresses).
- Fragmentation and reassembly of packets.

*Protocols:*
- IP (Internet Protocol)
- IPv4 (Internet Protocol version 4)
- IPv6 (Internet Protocol version 6)
- ICMP (Internet Control Message Protocol)
- IGMP (Internet Group Management Protocol)
- IPsec (Internet Protocol Security)


**3. Transport Layer**

*Description:*
The Transport Layer provides end-to-end communication services for applications. It ensures complete data transfer, error recovery, and flow control.

*Functions:*
- Establishes, maintains, and terminates connections.
- Ensures reliable data transfer and error recovery.
- Manages data flow to prevent congestion.

*Protocols:*
- TCP (Transmission Control Protocol)
- Ensures reliable, ordered, and error-checked delivery of data.
- UDP (User Datagram Protocol)
- Provides a connectionless, low-latency transmission method without reliability.


**4. Application Layer**

*Description:*
The Application Layer is the top layer in the TCP/IP model, which provides protocols and services for end-user applications. It enables software to communicate over the network.

*Functions:*
- Provides network services to applications.
- Interprets requests and data formats.

*Protocols:*
- HTTP (HyperText Transfer Protocol)
- HTTPS (HTTP Secure)
- FTP (File Transfer Protocol)
- SMTP (Simple Mail Transfer Protocol)
- POP3 (Post Office Protocol version 3)
- IMAP (Internet Message Access Protocol)
- DNS (Domain Name System)
- SSH (Secure Shell)


### Summary of TCP/IP Layers
**Network Interface Layer (Link Layer):** Handles the physical and data link aspects of network communication. **Ethernet and hardwares** *Frame*.

**Internet Layer:** Manages logical addressing and routing (IP). ***IP Protocol*** *Packets*.

**Transport Layer:** Ensures reliable data transfer (TCP, UDP). ***TCP Protocol*** *Segment*.

**Application Layer:** Provides protocols for specific applications and services (HTTP, FTP, SMTP, etc.). *PDU*



The TCP/IP model is crucial for understanding how data is transmitted across networks, and it provides a practical framework for networking concepts and implementations.
