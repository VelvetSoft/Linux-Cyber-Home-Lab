# Home Lab 005 - TCP Three-Way Handshake

## Objective

Learn how TCP establishes a connection using the three-way handshake process.

## Exercises

### Exercise 1 - Observe TCP Handshake

Findings:

Observed a complete TCP Three-Way Handshake using Wireshark.

Captured SYN, SYN-ACK and ACK packets between the local host and a remote server.

Observed TLS Client Hello and TLS Server Hello messages immediately after TCP connection establishment.

Verified how HTTPS communication starts in real network traffic.

## Lessons Learned

TCP uses a Three-Way Handshake before data transfer begins.

The client initiates the connection using a SYN packet.

The server responds with SYN-ACK.

The client confirms the connection with ACK.

After TCP establishment, TLS negotiation begins to create an encrypted HTTPS session.

Understanding TCP handshakes is essential for network troubleshooting and SOC investigations.
