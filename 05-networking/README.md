# Networking Fundamentals

## Overview

This section documents the networking fundamentals I learned during the TryHackMe Pre Security learning path.

The focus was on understanding how devices communicate, how network traffic is addressed and transported, and how common network services and security controls work.

---

## 1. OSI Model

The OSI (Open Systems Interconnection) model provides seven conceptual layers for understanding network communication:

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

### Key lesson

The OSI model helps break networking into separate layers, making it easier to understand where protocols, devices, and security controls operate.

---

## 2. TCP/IP

The TCP/IP model is used to describe how network communication works in practical environments.

Important protocols and concepts studied included:

- IP addressing
- TCP
- UDP
- ARP
- DHCP
- DNS
- HTTP/HTTPS
- Network ports

---

## 3. IP Addressing

An IP address identifies a device or network interface on an IP network.

### IPv4

IPv4 addresses contain four octets.

Each octet can have a value from 0–255.

Example: 192.168.1.10

### Subnet Masks

Subnet masks are used to determine which part of an IPv4 address represents the network and which part represents the host.

Subnetting allows networks to be divided into smaller logical networks.

---

## 4. MAC Addresses

A MAC (Media Access Control) address is associated with a network interface and operates at the Data Link layer.

MAC addresses are used for communication on a local network.

---

## 5. ARP

ARP (Address Resolution Protocol) is used to associate an IPv4 address with a MAC address on a local network.

### ARP Request

An ARP Request asks whether a device has a particular IP address.

### ARP Reply

The device that owns the requested IP address can respond with its MAC address.

### Security relevance

ARP is important to understand when studying local-network attacks such as ARP spoofing.

---

## 6. DHCP

DHCP (Dynamic Host Configuration Protocol) automatically provides network configuration to devices.

A key process learned was DORA:

1. Discover – the client searches for a DHCP server.
2. Offer – the server offers an IP address and configuration.
3. Request – the client requests the offered configuration.
4. ACK – the server confirms the lease.

### Key practical knowledge

A device uses a DHCP Discover packet to locate a DHCP server.

After receiving an offer, it sends a DHCP Request.

---

## 7. DNS

DNS (Domain Name System) translates domain names into IP addresses.

For example: example.com → IP address

### TTL

TTL (Time To Live) specifies how long a DNS record can be cached before it should be queried again.

### Security relevance

Understanding DNS is important when investigating domains, network traffic, phishing, and other security events.

---

## 8. TCP and UDP

### TCP

TCP (Transmission Control Protocol) is connection-oriented and designed to provide reliable communication.

It uses mechanisms such as acknowledgements and sequencing to help ensure reliable delivery.

### UDP

UDP (User Datagram Protocol) is connectionless and has less overhead than TCP.

It does not provide the same delivery guarantees as TCP.

### Comparison

| TCP | UDP |
|---|---|
| Connection-oriented | Connectionless |
| Reliable delivery mechanisms | No built-in delivery guarantee |
| More overhead | Lower overhead |
| Used where reliability matters | Useful where speed/low overhead matters |

---

## 9. TCP Three-Way Handshake

TCP uses a handshake to establish a connection.

The main packet sequence is:

1. SYN
2. SYN-ACK
3. ACK

This establishes the TCP connection before normal data communication begins.

### Practical lab

I worked with a simulated network log and learned to distinguish the entries associated with the handshake from other network events.

---

## 10. Ports

Ports help identify network services running on a device.

A network connection can be described using information such as:

- Source IP
- Destination IP
- Source port
- Destination port
- Protocol

Understanding ports is important for network troubleshooting, reconnaissance, and security monitoring.

---

## 11. Routers and Routing

A router connects networks and determines where network traffic should be forwarded.

The key function learned was:

Routing

Routers use network information to determine an appropriate path for packets.

---

## 12. Packets and Frames

Network communication is divided into smaller units of data.

- Packets are commonly associated with the Network layer.
- Frames are associated with the Data Link layer.

Understanding this distinction helps when analysing network traffic and troubleshooting communication.

---

## 13. Firewalls

A firewall controls network traffic according to defined rules.

The Pre Security material introduced firewalls as a security control used to allow or block traffic.

### Stateful firewall

A stateful firewall keeps track of the state of network connections and can make decisions based on the connection state.

### Stateless firewall

A stateless firewall evaluates individual packets against configured rules without maintaining the same connection-state awareness.

### OSI layers

The firewall exercise focused on:

- Network layer (Layer 3)
- Transport layer (Layer 4)

### Practical firewall lab

I worked with a simulated firewall where traffic was controlled using rules containing values such as:

- Source IP
- Destination IP
- Port
- Action

The exercise demonstrated why security rules should be specific rather than unnecessarily broad.

---

## 14. Network Logs

Network logs can contain different events associated with communication between systems.

During the Pre Security practical exercises, I learned to identify specific event types such as HANDSHAKE entries rather than counting unrelated log entries.

This is an important foundation for later security monitoring and SOC work.

---

## 15. Practical Knowledge Gained

During the networking section, I practised and reviewed:

- OSI model
- TCP/IP concepts
- IPv4 addressing
- Subnetting
- MAC addresses
- ARP requests and replies
- DHCP DORA process
- DNS and TTL
- TCP vs UDP
- TCP three-way handshake
- Ports
- Routing
- Packets and frames
- Firewall rules
- Stateful vs stateless firewalls
- Network log analysis

---

## 16. Cybersecurity Relevance

Networking is a core foundation for cybersecurity.

Understanding normal network behaviour makes it easier to recognise abnormal activity later.

These fundamentals will support future learning in areas such as:

- Network reconnaissance
- Traffic analysis
- SOC monitoring
- Incident response
- Threat detection
- SIEM investigations
- Network-based attacks and defences

---

## Key Takeaways

- The OSI model provides a structured way to understand network communication.
- IPv4 addresses identify devices/interfaces on IP networks.
- ARP maps IPv4 addresses to MAC addresses on local networks.
- DHCP can automatically provide network configuration using the DORA process.
- DNS resolves domain names and uses TTL to control caching duration.
- TCP provides connection-oriented, reliable communication mechanisms.
- UDP is connectionless and has lower overhead.
- TCP connections use SYN, SYN-ACK, and ACK during establishment.
- Routers perform routing between networks.
- Firewalls control traffic using rules.
- Network logs provide useful evidence for understanding network activity.

**Status: Completed — TryHackMe Pre Security**
