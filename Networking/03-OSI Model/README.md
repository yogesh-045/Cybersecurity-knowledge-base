## What is the OSI Model?

The OSI (Open Systems-Interconnection) Model is a conceptual framework developed by ISO (International Organization for Standardization). It standardizes how different networking systems communicate by dividing communication into 7 layers.

# Why is it Important?
Standardizes network communication.

Simplifies troubleshooting.

Helps understand data flow.

Promotes interoperability between vendors.

## The 7 Layers of the OSI Model
Layer   Name	     |    Main Function
7	    Application	 |   User-facing network services
6	    Presentation |	 Data translation, encryption, compression
5	    Session	      Establishes, manages, and terminates sessions
4	    Transport	 |    Reliable data delivery, segmentation
3	    Network	     |   Routing and logical addressing
2	    Data Link	 |   MAC addressing and error detection
1	    Physical	 |   Transmission of raw bits

# Layer 7 – Application Layer
Provides network services directly to end-user applications.

# Common Protocols

HTTP

HTTPS

FTP

SMTP

IMAP

POP3

DNS

SSH

# Examples

Chrome

Firefox

Outlook

Gmail

## Layer 6 – Presentation Layer
The Presentation layer is responsible for Data translation, formatting, Encryption, Decryption, and compression.

# Examples
SSL/TLS

JPEG

PNG

MP3

MPEG

## Layer 5 – Session Layer
The session layer manages session between two devices. session Maintain, Ends sessions.

# Examples

NetBIOS

RPC

SIP

## Layer 4 – Transport Layer
The transport layer ensures reliable delivery, End-to-end communication, retransmittion, segmentation and error checking between to devices. over (TCP/UDP) protocol.

# Protocols
TCP

UDP

## Layer 3 – Network Layer
The Network layer handles routing and logical addressing.

# Protocols
IP

ICMP

OSPF

RIP

BGP

# Device
Router

## Layer 2 – Data Link Layer
The Data link layer handles MAC addressing, framming, Error Detection.

# Protocols
Ethernet

PPP

ARP

STP

## Device
Switch
Bridge

## Layer 1 – Physical Layer
Transfers raw bits through the transmission medium.(0's and 1's)

# Devices
Hub

Repeater

Cables

Connectors

Media

Copper Cable

Fiber Optic

Wireless

# OSI Model
![OSI Model](image/osimodel.png)

## Real-World Example (Loading a Website)

When you open https://google.com:

Application – Browser creates an HTTP request.

Presentation – TLS encrypts the data.

Session – A secure session is established.

Transport – TCP breaks data into segments.

Network – IP routes packets to the server.

Data Link – Frames are created using MAC addresses.

Physical – Bits travel through Ethernet, Wi-Fi, or fiber.

The server receives the data and performs decapsulation in reverse order.

# Interview Questions

What is the OSI Model?

Who developed the OSI Model?

How many layers are in the OSI Model?

Which layer is responsible for routing?

Which layer uses MAC addresses?