Home Lab 004 - Wireshark Packet Capture
Objective

Learn how to capture and analyze DNS and HTTPS traffic using Wireshark.

Exercises
### Exercise 1 - Capture DNS Queries

Findings:

- Captured DNS traffic using Wireshark.
- Observed a DNS query for tryhackme.com.
- Observed a DNS response containing IP addresses.
- Identified the DNS server as 1.1.1.1.
- Learned how DNS requests and responses appear in network traffic.


### Exercise 2 - Capture HTTPS Connections

Findings:

- Captured encrypted HTTPS traffic using Wireshark.
- Observed TLSv1.3 communication.
- Identified traffic between the local host and GitHub servers.
- Learned that HTTPS traffic is encrypted and cannot be read directly.
- Observed TLS application data packets.

Lessons Learned

- DNS queries and responses can be observed directly in network traffic.
- Wireshark allows packet-level inspection of network communication.
- HTTPS traffic uses TLS encryption and cannot be read directly.
- DNS resolution happens before connecting to a website.
- Network protocols can be analyzed using packet captures.
