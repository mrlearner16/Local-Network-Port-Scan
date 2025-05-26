# Local-Network-Port-Scan
"Nmap scan of local network for Elevate Labs Cybersecurity Internship Task 1."
# CYBER SECURITY INTERNSHIP

 Task Overview
Performed a TCP SYN scan (`nmap -sS`) on a local host (`192.168.1.3`) to identify open ports and assess potential security exposures.
nmap -sS 192.168.1.3

## 🔍 Scan Results
``
Nmap scan report for 192.168.1.3
Host is up (0.0020s latency).
Not shown: 993 filtered tcp ports (no-response)
PORT    STATE SERVICE
135/tcp open  msrpc
139/tcp open  netbios-ssn
445/tcp open  microsoft-ds
903/tcp open  iss-console-mgr
5357/tcp open wsdapi
8000/tcp open http-alt
8089/tcp open unknown


# Tools Used
Tool	Purpose	Command Example
Nmap 7.94	Port scanning	nmap -sS 192.168.1.3
Wireshark	Packet analysis	Filter: tcp.port == 80
Kali Linux	Penetration testing environment	-

 # Key Learnings
Network Mapping: Identified 7 open ports exposing services

Traffic Patterns: Recognized normal vs suspicious TCP handshakes

Virtual Networks: Analyzed VMware-hosted traffic

Defense Strategies: Learned port hardening techniques
