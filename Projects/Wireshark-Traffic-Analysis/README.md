# Network Traffic Analysis using Wireshark 

## Objectives
To capture and analyze network traffic and identify common protocols used during web browsing.

## Tools Used 
- Wireshark
- Windows 11

## Procedure 
1. Installed Wireshark
2. Captured live network traffic on the Wi-Fi interface
3. Browsed websites such as Google and youtube.
4. Applied DNS, TCP, and TLS filters.
5. Analyzed captured packets.

## DNS Analysis
Observed DNS queries and responses for domains such as Google and Brave services.
DNS translated domain names into IP addresses

## TCP Analysis 
Observed TCP ACK, FIN, and RST packets.
Verified reliable client- server
communication and connection termination

## TLS Analysis
Observed TLSv1.3 Client Hello and Server Hello messages. Verified encrypted HTTPS communication and identified SNI information

## Findings
- DNS was used for domain resolution.
- TCP provided reliable communication.
- TLS encrypted web traffic.
- HTTPS communication occured over port 443.
- No suspicious activity was observed.

## Skills Demonstraded 
- Packet Analysis
- Network Monitoring
- Protocol Analysis
- Traffic Investigation
- Wireshark usage.
