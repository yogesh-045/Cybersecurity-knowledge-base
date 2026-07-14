# What is the TCP/IP Model?

The TCP/IP (Transmission Control Protocol/Internet Protocol) Model is the standard networking model used on the Internet. It defines how devices communicate over a network by organizing communication into four layers.

Unlike the OSI Model, which is mainly a conceptual reference model, the TCP/IP Model is practical and is used in real-world networks.

# Why is the TCP/IP Model Important?
Foundation of the Internet

Standard communication model

Supports routing across networks

Vendor-independent

Highly scalable and reliable

# The 4 Layers of the TCP/IP Model

| Layer | Name            | Main Function |
|:-----:|------|----------|
| **4** | **Application** | Provides network services to users  and applications |
| **3** | **Transport**  | End-to-end communication, segmentation, reliability, flow control, and error recovery |
| **2** | **Internet**   | Logical addressing, routing, packet forwarding, and path selection |
| **1** | **Network Access** | Physical transmission, framing, MAC addressing, and communication over the network                                      medium |


# Layer 4 – Application Layer

Provides services directly to end-user applications.

# Common Protocols

HTTP

HTTPS

FTP

DNS

SMTP

POP3

IMAP

SSH

DHCP
# Examples

Chrome

Firefox

Outlook

Gmail

# Layer 3 – Transport Layer

End-to-end communication

Segmentation

Flow control

Error recovery

Reliable delivery

# Protocols

TCP

UDP

# Layer 2 – Internet Layer

IP Addressing

Routing

Packet forwarding

Path selection

# Protocols

IPv4

IPv6

ICMP

IGMP

# Device
Router

# Layer 1 – Network Access Layer

Handles communication between devices on the same network and transmits data over the physical medium.

# Technologies
Ethernet

Wi-Fi

Fiber Optic

DSL

# Devices
Switch

NIC

Hub

Access Point

# Encapsulation
Data
   ↓
Segment
   ↓
Packet
   ↓
Frame
   ↓
Bits

# Decapsulation
Bits
   ↑
Frame
   ↑
Packet
   ↑
Segment
   ↑
Data

# Advantages

Used worldwide

Scalable

Reliable

Supports routing

Open standard

Compatible with all major operating systems

## TCP/IP Model
[TCP/IP Model](image/tcpip.png)

# Real-World Example

When you visit https://example.com:

Application Layer – Browser creates an HTTPS request.

Transport Layer – TCP establishes a reliable connection.

Internet Layer – IP routes packets to the destination.

Network Access Layer – Ethernet or Wi-Fi transmits the frames over the network.

The destination host then performs decapsulation to process the received data.

# Interview Questions

What is the TCP/IP Model?

How many layers are in the TCP/IP Model?

Which layer is responsible for routing?

Which protocols work at the Transport Layer?

What is the difference between TCP and UDP?
