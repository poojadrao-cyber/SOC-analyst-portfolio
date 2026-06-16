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
## Screenshot
### DNS Analysis
<img width="2551" height="1438" alt="dns-analysis" src="https://github.com/user-attachments/assets/3c29a5ec-b007-4487-a057-141e0f1e56dd" />




## TCP Analysis 
Observed TCP ACK, FIN, and RST packets.
Verified reliable client- server
communication and connection termination
## Screenshot
### TCP Analysis
<img width="2549" height="1433" alt="tcp-analysis" src="https://github.com/user-attachments/assets/8674c180-4787-4e6b-ba55-24d4ca060f48" />




## TLS Analysis
Observed TLSv1.3 Client Hello and Server Hello messages. Verified encrypted HTTPS communication and identified SNI information
## Screenshot
### TLS Analysis
<img width="2556" height="1439" alt="tls-analysis" src="https://github.com/user-attachments/assets/c685ff3d-d315-4444-8d18-8048b2a87f45" />



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
