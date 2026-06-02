# Home Lab 001 - Network Reconnaissance

## Objective

Identify active hosts and enumerate services within a local network.

## Tools Used

- ip
- ping
- nmap

## Commands Executed

- ip a
- ip route
- ping -c 4 <gateway>
- nmap -sn <subnet>/24
- nmap -sV <gateway>

## Findings

Discovered devices:

- Gateway / Repeater
- Windows Workstation
- Linux Virtual Machine

Discovered services:

- Telnet (23/tcp)
- DNS (53/tcp)
- HTTP (80/tcp)

Detected software:

- BusyBox telnetd
- lighttpd 1.4.32

## Security Observations

- Telnet service enabled.
- HTTP management interface accessible.
- Service enumeration completed successfully.

## Skills Practiced

- Host discovery
- Service enumeration
- Linux networking
- Basic security assessment
