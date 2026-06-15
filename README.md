# Linux Cyber Home Lab



| Lab | Topic | Status |
|------|--------|--------|
| 001 | Network Discovery | ✅ |
| 002 | DNS Investigation | ✅ |
| 003 | HTTP & Web Requests | ✅ |
| 004 | Wireshark Packet Capture | ✅ |
| 005 | TCP Three-Way Handshake| ✅ |
| 006 | Linux Log Analysis | ✅ |
| 007 | Linux Users, Groups & Permissions | ✅ |

## Overview

This repository documents my hands-on cybersecurity learning journey using Ubuntu Linux, VirtualBox, networking tools and practical home lab exercises.

The goal of this project is to build practical skills required for junior cybersecurity and SOC analyst roles through real-world exercises and documentation.

## Skills Practiced

* Linux command line
* Network fundamentals
* DNS investigation
* Network reconnaissance
* Service enumeration
* Basic security analysis
* Git and GitHub workflow
* Technical documentation
* Packet analysis
* Wireshark
* TLS/HTTPS investigation
* TCP/IP fundamentals
* Traffic analysis
* Linux log analysis
* journalctl
* grep filtering
* Security event investigation

## Home Labs

### Home Lab 001 – Network Discovery

Topics:

* Host discovery
* Nmap scanning
* Service enumeration
* Local network analysis

Key findings:

* Identified active hosts in the local network
* Detected open services and ports
* Practiced network reconnaissance techniques

### Home Lab 002 – DNS Investigation

Topics:

* DNS resolution
* WHOIS lookups
* Traceroute analysis
* Network path investigation

Key findings:

* Identified active DNS servers
* Resolved domain names to IP addresses
* Traced traffic path to GitHub
* Verified IP ownership using WHOIS

### Home Lab 003 – HTTP & Web Requests

Topics:

- HTTP and HTTPS
- HTTP response headers
- GET and HEAD requests
- Website redirects
- Basic web traffic analysis

Key findings:

- Analyzed HTTP response headers using curl
- Observed differences between HEAD and GET requests
- Retrieved HTML content from a web server
- Identified HTTP to HTTPS redirection using status code 301
- Learned how modern websites enforce encrypted connections

### Home Lab 004 – Wireshark Packet Capture

Topics:

- Packet capture
- DNS traffic analysis
- HTTPS/TLS traffic analysis
- Wireshark basics
- Network traffic inspection

Key findings:

- Captured DNS queries and responses using Wireshark
- Identified communication with DNS server 1.1.1.1
- Observed DNS resolution process in network traffic
- Captured encrypted HTTPS traffic
- Observed TLSv1.3 communication with GitHub servers
- Learned how DNS and HTTPS appear at packet level

## Home Lab 005 – TCP Three-Way Handshake

Topics:

- TCP protocol
- TCP Three-Way Handshake
- SYN packets
- SYN-ACK packets
- ACK packets
- TLS handshake introduction

Key findings:

- Captured a complete TCP Three-Way Handshake using Wireshark.
- Observed SYN, SYN-ACK and ACK packets.
- Identified how TCP connections are established before data transfer.
- Observed TLS Client Hello and Server Hello messages.
- Learned how HTTPS communication begins at the network level.

## Home Lab 006 – Linux Log Analysis

Topics:

- Linux system logs
- journalctl
- grep filtering
- Failed event investigation
- AppArmor security events
- SSH log analysis

Key findings:

- Reviewed Linux system logs using journalctl
- Investigated failed system events
- Analyzed AppArmor security denials
- Examined SSH-related log entries
- Learned to distinguish between errors and security controls
- Practiced filtering security-relevant events with grep


## Home Lab 007 – Linux Users, Groups & Permissions

Topics:

- Linux users
- Linux groups
- File permissions
- chmod
- Numeric permissions
- Symbolic permissions
- Access control

Key findings:

- Identified the current Linux user and associated groups.
- Investigated file and directory permissions using ls -l.
- Learned the difference between owner, group and others.
- Interpreted Linux permission notation (rwx).
- Modified permissions using chmod.
- Applied common permission configurations such as 644, 700 and 755.
- Practiced symbolic permission changes using chmod u+x.


## Tools Used

* Ubuntu Linux
* VirtualBox
* Nmap
* nslookup
* traceroute
* whois
* curl
* Wireshark
* UFW
* Git
* GitHub

## Learning Goal

Develop practical cybersecurity skills and build a documented portfolio for entry-level cybersecurity positions.

