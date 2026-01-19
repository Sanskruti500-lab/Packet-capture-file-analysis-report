# Packet-capture-file-analysis-report
1️⃣ Basic Networking Concepts (Very Simple)

🔹 IP Address
	•	IP address is like your home address on the internet
	•	Example: 192.168.1.1
	•	It helps devices find each other

🔹 MAC Address
	•	MAC address is a unique hardware address of a device
	•	Example: 00:1A:2B:3C:4D:5E
	•	It never changes

🔹 DNS (Domain Name System)
	•	DNS converts website name → IP address
	•	Example: google.com → 142.250.182.14

🔹 TCP (Transmission Control Protocol)
	•	Reliable
	•	Used for websites, emails
	•	Data arrives in order

🔹 UDP (User Datagram Protocol)
	•	Fast but not reliable
	•	Used for video streaming, online games

⸻

2️⃣ Install Wireshark & Capture Live Traffic

Steps:
	1.	Download Wireshark from wireshark.org
	2.	Install and open Wireshark
	3.	Select your Wi-Fi or Ethernet interface
  Observe TCP Three-Way Handshake

TCP connection has 3 steps:
	1.	SYN – Client asks to connect
	2.	SYN-ACK – Server accepts
	3.	ACK – Client confirms
  5️⃣ Plain-Text vs Encrypted Traffic

🔓 Plain-Text
	•	Protocol: HTTP
	•	Data is readable
	•	Username/password can be seen

🔒 Encrypted
	•	Protocol: HTTPS (TLS)
	•	Data is encrypted
	•	Content not readable
  Save Packet Capture File

Steps:
	1.	Stop capture
	2.	Go to File → Save As
	3.	Save as .pcap file

📁 Example: network_capture.pcap

This file is used for future analysis or submission

⸻

8️⃣ Observations (Simple Language)
	•	IP address identifies devices on a network
	•	MAC address is unique for every device
	•	DNS converts website names into IP addresses
	•	TCP uses a three-way handshake to create connection
	•	HTTP traffic is not secure and readable
	•	HTTPS traffic is encrypted and secure
	•	Wireshark helps monitor real network data

⸻

✅ Conclusion

This experiment helps us understand how data travels on a network and how to analyze traffic using Wireshark.
  

  
