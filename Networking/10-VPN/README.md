# VPN (Virtual Private Network)

A Virtual Private Network (VPN) is a technology that creates a secure and encrypted connection over a public network (such as the Internet), allowing users or networks to communicate safely while protecting the confidentiality, integrity, and privacy of the transmitted data.

## Why is VPN Used?
 Encrypts data to protect it from attackers.

 Provides secure remote access to private networks.

 Protects sensitive information over public Wi-Fi.

 Hides the user's IP address and enhances privacy.

 Allows secure communication between branch offices.

## How VPN Works

1. A user connects to a VPN server.

2. The VPN client authenticates the user.

3. A secure, encrypted tunnel is established.

4. All data passes through the encrypted tunnel.

5. The VPN server decrypts the data and forwards it to the destination.

## Types of VPN

| Type | Description |
|------|-------------|
| **Site-to-Site VPN** | Connects two or more private networks securely over the Internet. |
| **Remote Access VPN** | Allows individual users to securely access an organization's network from remote locations. |
| **IPSec VPN** | Uses the IPSec protocol to provide encryption, authentication, and data integrity at the IP layer. |
| **SSL VPN** | Uses SSL/TLS to provide secure remote access through a web browser or VPN client. |

## Advantages

 Secure communication

 Data encryption

 Remote access

 Protects sensitive information

 Enhances privacy

## Disadvantages

 May reduce Internet speed due to encryption

 Requires proper configuration

 Some VPN services can be expensive

# Site to Site VPN
A Site-to-Site VPN securely connects two or more geographically separated networks over the Internet, allowing users at each location to communicate as if they were on the same local network.

# How It Works
A VPN tunnel is established between two VPN gateways (routers or firewalls).

Data is encrypted before it is sent over the Internet.

The receiving gateway decrypts the data and forwards it to the 
destination network.

# Example
Branch Office
    |
Encrypted VPN Tunnel
    |
Head Office

# Use Cases
Connecting branch offices to headquarters

Secure communication between company locations

# Remote Access VPN
A Remote Access VPN allows individual users to securely connect to a private network from any location using the Internet.

# How It Works
User opens a VPN client.

User authenticates with username/password or MFA.

An encrypted tunnel is created.

The user securely accesses company resources.

# Example
Employee Laptop
      |
Encrypted VPN Tunnel
      |
Company Network

# Use Cases
Work from home

Remote employees

Secure access while traveling

# IPSec
IPSec (Internet Protocol Security) is a suite of protocols that secures IP communication by providing authentication, integrity, and encryption.

# Features
Encrypts data

Authenticates devices

Ensures data integrity

Protects against packet tampering

## IPSec Modes

| Mode | Description |
|------|-------------|
| **Transport Mode** | Encrypts only the **payload (data)** of the IP packet, while the original IP header remains unchanged. Commonly used for end-to-end communication between two hosts. |
| **Tunnel Mode** | Encrypts the **entire IP packet** (header and payload) by encapsulating it inside a new IP packet. Commonly used for Site-to-Site VPNs. |

## Common IPSec Protocols

| Protocol | Purpose |
|----------|---------|
| **AH (Authentication Header)** | Provides **authentication**, **data integrity**, and protection against replay attacks, but **does not encrypt** the data. |
| **ESP (Encapsulating Security Payload)** | Provides **encryption**, **authentication**, **data integrity**, and protection against replay attacks. It is the most commonly used IPSec protocol. |


# SSL VPN
An SSL VPN (Secure Sockets Layer VPN) provides secure remote access to applications or networks using SSL/TLS encryption through a web browser or VPN client.

# Features
Uses SSL/TLS encryption

Can work through a web browser

Easy for remote users

No dedicated VPN hardware required for users

# Example
Remote User
      |
HTTPS (SSL/TLS)
      |
Company VPN Gateway
      |
Internal Network

# Advantages
Easy deployment

Secure remote access

Supports web-based applications

Works across most networks without special configuration


# Wireless Networking
A Wireless Network is a type of computer network that allows devices to communicate without using physical cables. Instead, it uses radio waves to transmit data between devices and a wireless access point (AP) or router.

# How Wireless Networking Works
A wireless device (laptop, smartphone, etc.) connects to a Wi-Fi network.

The Access Point (AP) receives the wireless signal.

The AP forwards the data to the router.

The router sends the data to the Internet or another network.

# Advantages
Mobility and flexibility

Easy installation

No physical cables required

Supports multiple devices

# Disadvantages
Lower speed than wired networks

Signal interference

Limited range

Security risks if not properly configured

# WiFi Standards
Wi-Fi Standards are IEEE 802.11 protocols that define how wireless devices communicate, including speed, frequency, and performance.

## Common Wi-Fi Standards

| Standard | IEEE Version | Frequency Band | Maximum Speed |
|----------|--------------|----------------|---------------|
| **Wi-Fi 4** | **802.11n** | 2.4 GHz / 5 GHz | Up to **600 Mbps** |
| **Wi-Fi 5** | **802.11ac** | 5 GHz | Up to **3.5 Gbps** |
| **Wi-Fi 6** | **802.11ax** | 2.4 GHz / 5 GHz | Up to **9.6 Gbps** |
| **Wi-Fi 6E** | **802.11ax** | 2.4 GHz / 5 GHz / 6 GHz | Up to **9.6 Gbps** |
| **Wi-Fi 7** | **802.11be** | 2.4 GHz / 5 GHz / 6 GHz | Up to **46 Gbps (Theoretical)** |

# WPA2
WPA2 (Wi-Fi Protected Access 2) is a wireless security protocol introduced in 2004. It uses AES (Advanced Encryption Standard) to protect wireless communications.

# Features
AES encryption

Strong authentication

Widely supported

Suitable for home and enterprise networks

# Advantages
Strong encryption

Better security than WEP and WPA

Widely compatible

Limitation

Vulnerable to weak passwords and certain attacks (e.g., KRACK if systems are unpatched)

# WPA3
WPA3 (Wi-Fi Protected Access 3) is the latest Wi-Fi security standard that provides stronger authentication and encryption than WPA2.

# Features
Stronger password protection

Uses SAE (Simultaneous Authentication of Equals)

Improved resistance to brute-force attacks

Better protection on public Wi-Fi

# Advantages
Higher security

Better encryption

Protection against offline password attacks

# Wireless Security
Wireless Security refers to the technologies and best practices used to protect wireless networks from unauthorized access, attacks, and data theft.

## Common Wireless Security Methods

| Security Method | Description |
|-----------------|-------------|
| **WEP (Wired Equivalent Privacy)** | An outdated and insecure wireless encryption standard that is vulnerable to multiple security attacks. |
| **WPA (Wi-Fi Protected Access)** | Improved security over WEP by introducing stronger encryption, but it is now considered outdated. |
| **WPA2 (Wi-Fi Protected Access 2)** | Uses **AES (Advanced Encryption Standard)** encryption and is widely used in home and enterprise wireless networks. |
| **WPA3 (Wi-Fi Protected Access 3)** | The latest and most secure Wi-Fi security standard, offering stronger authentication and protection against brute-force attacks. |
| **MAC Address Filtering** | Restricts network access by allowing only devices with approved MAC addresses to connect. |
| **Hidden SSID** | Prevents the wireless network name (SSID) from being broadcast, making the network less visible to nearby devices. |

# Best Practices
Use WPA3 whenever possible.

Use a strong Wi-Fi password.

Change default router credentials.

Disable WPS.

Keep router firmware updated.

Enable a firewall on the router.


