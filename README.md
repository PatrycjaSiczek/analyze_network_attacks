## analyze_network_attacks
## Project Overview
This project is part of my cybersecurity learning journey. The goal was to analyze network traffic logs and identify a possible cyberattack affecting a company's website.

## Tools and Technologies
- Wireshark (network traffic log analysis)
- TCP/IP
- HTTP
- Network Security

## Incident Description
Employees reported problems accessing the company's website. The website was loading slowly, and some users received connection timeout errors.
After analyzing the network logs, I identified a possible SYN flood DoS attack.

## Analysis
The logs showed that:
- IP address 203.0.113.0 was sending many SYN requests to the web server.
- The server was becoming overloaded.
- Users started receiving HTTP 504 Gateway Time-out errors.
- Eventually, the server stopped responding to normal requests.

## Conclusion
The incident was caused by a SYN flood DoS attack. Too many SYN requests overloaded the server and prevented employees from accessing the website.
This project helped me understand how SYN flood attacks work and how network logs can be used to identify security incidents.

## Skills Practiced
- Network traffic analysis
- Identifying suspicious TCP packets
- Understanding DoS attacks
- Analyzing HTTP errors
- Writing cybersecurity incident reports
