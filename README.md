# Network-Scanning-using-Nmap
**Introduction**

Nmap (Network Mapper) is a powerful open-source tool used for network discovery and security auditing. It helps identify hosts, open ports, running services, and even operating systems on a network.

**Installation**

Linux: sudo apt install nmap
Windows: Download from the official Nmap site

**Basic Commands**

Command	Description
nmap <target>	Basic scan of target host
nmap -p 80 <target>	Scan a specific port (80)
nmap -p 1-1000 <target>	Scan a range of ports
nmap -sV <target>	Detect service versions
nmap -O <target>	Operating system detection
nmap -A <target>	Aggressive scan (OS + services + traceroute)

**Practical Examples**
nmap 192.168.1.10
nmap 192.168.1.0/24
nmap -sV 192.168.1.10

**Key Features Using Nmap**

Host discovery: Identify which devices are active on a network.
Port scanning: Enumerate open ports on target systems.
Service/version detection: Determine which applications and versions are running.
OS fingerprinting: Detect the operating system of remote hosts.
Nmap Scripting Engine (NSE): Automate tasks like vulnerability detection and advanced service checks using Lua scripts.
Flexible output formats: Save results in normal text, XML, or multiple formats simultaneously.

**Typical Use Cases**
Network inventory: Map devices and services across an organization.
Firewall testing: Check which ports are accessible through firewalls.
Vulnerability assessment: Identify weak points in systems.
Penetration testing: Reconnaissance before deeper exploitation.
System administration: Monitor uptime, manage upgrades, and troubleshoot connectivity issues

**Scan Report**

Scan Report www.raisoni.net

<img width="1586" height="869" alt="image" src="https://github.com/user-attachments/assets/b3a37c13-e152-4348-915f-ff9b7846d720" />
<img width="1586" height="869" alt="image" src="https://github.com/user-attachments/assets/9860e1c1-5561-42dd-b8a7-aeb03aa580f1" />
![Uploading image.png…]()


