# Home Lab 002 - DNS Investigation

## Objective

Learn how DNS resolves domain names into IP addresses.

## Commands Used

### Check DNS configuration

```bash
cat /etc/resolv.conf
resolvectl status


DNS lookups
nslookup tryhackme.com
nslookup github.com
Connectivity testing
ping github.com -c 4
ping 140.82.121.3 -c 4
Route analysis
traceroute github.com
WHOIS lookup
whois 140.82.121.3
Findings
Local DNS resolver: 127.0.0.53
Active DNS server: 1.1.1.1
GitHub IP resolved successfully
Route passed through Warsaw and Frankfurt
GitHub hides some traceroute hops
DNS translates domain names into IP addresses
Lessons Learned

A computer must first resolve a domain name through DNS before it can connect to a website.
