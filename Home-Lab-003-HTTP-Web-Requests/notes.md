# Home Lab 003 - HTTP & Web Requests

## Objective

Learn how web browsers communicate with web servers using HTTP and HTTPS.

## Exercises

### Exercise 1 - HTTP Headers

Command:

```bash
curl -I https://example.com

Findings:

- Sent a HEAD request using curl.
- Server responded with HTTP/2 200 OK.
- Content-Type was text/html.
- Website was protected by Cloudflare.
- Observed response headers without downloading page content.


### Exercise 2 - HTTP GET Request

Findings:

- Sent a GET request using curl.
- Server returned HTML content.
- Observed the source code of a web page.
- Learned the difference between HEAD and GET requests.



### Exercise 3 - HTTP Redirect


Findings:

- Sent a HEAD request to the HTTP version of GitHub.
- Server responded with HTTP/1.1 301 Moved Permanently.
- Observed a redirect to the HTTPS version of the website.
- Learned how websites enforce encrypted connections.




## Lessons Learned

- DNS resolves domain names into IP addresses.
- HTTP uses requests and responses between clients and servers.
- HEAD requests return headers only.
- GET requests return the full content of a webpage.
- Modern websites redirect HTTP traffic to HTTPS for security.
