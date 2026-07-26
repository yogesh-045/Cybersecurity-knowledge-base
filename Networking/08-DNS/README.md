# DNS Resolution
DNS (Domain Name System) Resolution is the process of converting a domain name (e.g., google.com) into its corresponding IP address (e.g., 142.250.183.206). This allows devices to locate and communicate with the correct server on the internet.

# How It Works
1.User enters a domain name in the browser.

2.Browser checks its DNS cache.

3.If not found, the request goes to the local DNS resolver.

4.Resolver queries Root DNS Server.

5.Root server points to the TLD (.com) server.

6.TLD server points to the Authoritative DNS server.

7.Authoritative server returns the IP address.

8.Browser connects to the server using the IP address.

# Example
google.com → 142.250.183.206

# Interview Questions

# Q: Why is DNS required?
 Because humans remember domain names easily, while computers communicate using IP addresses.

# DNS Record Types
DNS records store information about a domain and tell DNS servers how to respond to queries.


## Common DNS Record Types

| Record Type | Purpose |
|-------------|---------|
| **A** | Maps a domain name to an **IPv4** address. |
| **AAAA** | Maps a domain name to an **IPv6** address. |
| **CNAME** | Creates an alias that points one domain name to another domain name. |
| **MX** | Specifies the mail server responsible for receiving emails for a domain. |
| **NS** | Identifies the authoritative Name Servers for a domain. |
| **TXT** | Stores text-based information such as domain verification, SPF, DKIM, and other security-related records. |
| **PTR** | Used for **Reverse DNS Lookup** to map an IP address back to a domain name. |
| **SOA** | Contains administrative information about the DNS zone, including the primary name server, administrator email, serial number, and refresh intervals. |


# Example
example.com → A → 192.168.1.10

# Interview Question

Q: Which DNS record is used for email?

 MX Record.

# Forward Lookup
Forward Lookup is the process of finding an IP address from a domain name.

# Example
google.com

↓

142.250.183.206

# Use Case

Used every time you visit a website.

# Interview Question

Q: What does Forward Lookup return?

 The IP address of a domain.

# Reverse Lookup
Reverse Lookup is the process of finding a domain name from an IP address.

# Example
8.8.8.8
   |
dns.google
   |
Record Used
   |
PTR Record

# Use Case
Email server verification

Security investigations

Log analysis

# Interview Question

Q: Which record is used in Reverse Lookup?

 PTR Record.


# DORA Process

DORA is the four-step process used by DHCP to assign an IP address to a client.

# Steps
1. Discover

Client broadcasts a request for a DHCP server.

2. Offer

DHCP server offers an available IP address.

3. Request

Client requests the offered IP address.

4. Acknowledge

DHCP server confirms and leases the IP address.

# Diagram
Client
   |
Discover
   |
DHCP Server
   |
Offer
   |
Client
   |
Request
   |
DHCP Server
   |
ACK

# Interview Question
Q: What does DORA stand for?

 Discover, Offer, Request, Acknowledge.

# DHCP Lease

A DHCP Lease is the period of time for which a client is allowed to use an assigned IP address.

# Example
Lease Time = 24 Hours

Client gets IP: 192.168.1.20

After the lease expires, the client renews or receives a new IP address.

# Interview Question
Q: What happens when a DHCP lease expires?

 The client renews the lease or requests a new IP address.

# Static NAT
Static NAT creates a permanent one-to-one mapping between a private IP and a public IP.

# Example
192.168.1.10
↓
203.0.113.10

# Use Case

Hosting web servers or mail servers.


# Dynamic NAT
Dynamic NAT maps private IP addresses to a pool of available public IP addresses dynamically.

# Example
Private IP Pool

192.168.1.10

192.168.1.20

↓

Public Pool

203.0.113.1

203.0.113.2

# Use Case

Organizations with multiple public IP addresses.


# PAT (Port Address Translation)
PAT allows multiple devices to share a single public IP address by using different port numbers.

# Example
192.168.1.10:5000

192.168.1.20:6000

192.168.1.30:7000

↓

203.0.113.5

# Use Case
Used in almost all home routers.


# Static Routing
Static Routing is a routing method where routes are manually configured by the network administrator.

# Advantages
Secure

Predictable

Low CPU usage

# Disadvantages
Not scalable

Manual updates required

# Dynamic Routing
Dynamic Routing automatically learns and updates routes using routing protocols.

# Common Protocols
RIP

OSPF

EIGRP

BGP

# Advantages
Automatic updates

Scalable

Better fault tolerance

# RIP
Routing Information Protocol (RIP) is a distance-vector routing protocol that uses hop count as its routing metric.

Maximum Hop Count
15

16 hops = Unreachable

# OSPF
Open Shortest Path First (OSPF) is a link-state routing protocol that calculates the shortest path using the SPF (Shortest Path First) algorithm.

# Advantages
Fast convergence

Highly scalable

Supports large enterprise networks

# BGP
Border Gateway Protocol (BGP) is the routing protocol used to exchange routing information between different Autonomous Systems (AS) on the Internet.

# Use Case
Internet Service Providers (ISPs) and large enterprises.

# VLAN
A Virtual LAN (VLAN) logically divides a physical network into separate broadcast domains.

# Benefits
Improved security

Better performance

Easier management

# Example
VLAN 10 → HR

VLAN 20 → IT

VLAN 30 → Finance

# Trunking
Trunking allows multiple VLANs to travel over a single physical link between network devices.

# Protocol
IEEE 802.1Q


# STP (Spanning Tree Protocol)
STP prevents Layer 2 network loops by blocking redundant paths while keeping them available as backups.

# Benefits
Prevents broadcast storms

Prevents switching loops

Improves network stability

# Inter-VLAN Routing
Inter-VLAN Routing enables communication between devices located in different VLANs using a Layer 3 device (router or Layer 3 switch).

# Example
VLAN 10

↓

Layer 3 Switch

↓

VLAN 20


