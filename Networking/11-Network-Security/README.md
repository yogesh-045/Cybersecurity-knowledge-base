# Network Security
Network Security is the practice of protecting computer networks, devices, and data from unauthorized access, cyberattacks, misuse, and data breaches. It uses various security technologies, policies, and controls to ensure the Confidentiality, Integrity, and Availability (CIA Triad) of network resources.

# Objectives
Prevent unauthorized access

Protect sensitive data

Detect and respond to cyber threats

Ensure network availability

Maintain data confidentiality and integrity

## Common Network Security Technologies

| Technology | Purpose |
|------------|---------|
| **Firewall** | Filters incoming and outgoing network traffic based on predefined security rules. |
| **IDS (Intrusion Detection System)** | Monitors network traffic and detects suspicious or malicious activities. |
| **IPS (Intrusion Prevention System)** | Detects, prevents, and automatically blocks malicious network traffic in real time. |
| **Proxy Server** | Acts as an intermediary between users and the Internet to improve security, privacy, and content filtering. |
| **WAF (Web Application Firewall)** | Protects web applications from attacks such as SQL Injection (SQLi), Cross-Site Scripting (XSS), and other web-based threats. |
| **Zero Trust** | A security model based on the principle of **"Never Trust, Always Verify,"** requiring continuous authentication and authorization for every access request. |


# Firewall
A Firewall is a network security device or software that monitors and filters incoming and outgoing network traffic based on predefined security rules.

## Types of Firewalls

| Type | Description |
|------|-------------|
| **Packet Filtering Firewall** | Filters network packets based on IP address, port number, and protocol. |
| **Stateful Firewall** | Monitors active connections and filters traffic based on the state of the connection. |
| **Next-Generation Firewall (NGFW)** | Combines traditional firewall capabilities with advanced features such as application awareness, IDS/IPS, malware protection, and Deep Packet Inspection (DPI). |

# Advantages
Blocks unauthorized access

Filters malicious traffic

Protects internal networks


# IDS (Intrusion Detection System)
An Intrusion Detection System (IDS) monitors network or system activity to detect suspicious behavior and security threats. It generates alerts but does not block attacks.

## Types of IDS

| Type | Description |
|------|-------------|
| **Network IDS (NIDS)** | Monitors network traffic across an entire network segment to detect suspicious or malicious activities. |
| **Host IDS (HIDS)** | Monitors the activities, system logs, file integrity, and processes of a specific host or endpoint to detect security threats. |

# Features
Detects attacks

Generates alerts

Supports forensic investigations

# IPS (Intrusion Prevention System)
An Intrusion Prevention System (IPS) monitors network traffic, detects malicious activity, and automatically blocks or prevents attacks in real time.

# Features
Detects threats

Blocks malicious traffic

Prevents exploits

Works inline with network traffic

# Proxy Server
A Proxy Server acts as an intermediary between a client and the Internet. It receives requests from users, forwards them to the destination server, and returns the response.

# Advantages
Hides client IP addresses

Improves privacy

Filters web traffic

Can cache frequently accessed content

# WAF (Web Application Firewall)
A Web Application Firewall (WAF) protects web applications by filtering and monitoring HTTP/HTTPS traffic. It defends against common web attacks.

# Protects Against
SQL Injection (SQLi)

Cross-Site Scripting (XSS)

Cross-Site Request Forgery (CSRF)

File Inclusion attacks

# Advantages

Protects web applications

Blocks OWASP Top 10 attacks

Improves application security

# Zero Trust
Zero Trust is a cybersecurity model based on the principle of "Never Trust, Always Verify." Every user, device, and application must be authenticated and authorized before accessing resources, regardless of whether they are inside or outside the network.

# Core Principles
Never Trust, Always Verify

Least Privilege Access

Multi-Factor Authentication (MFA)

Continuous Monitoring

Assume Breach

# Advantages
Reduces insider threats

Limits unauthorized access

Improves overall security posture
