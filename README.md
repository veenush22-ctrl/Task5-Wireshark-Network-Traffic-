Task 5 – Capture and Analyze Network Traffic using Wireshark
Objective
To capture live network packets using Wireshark, apply filters to identify different protocols, and analyze the packet details to understand network communication.

Steps Performed
Installed Wireshark and selected the active network interface.

Started packet capture by clicking the shark-fin icon.

Generated network traffic by browsing websites and using the ping command.

Stopped capture after about 1 minute.

Applied filters (e.g., ip.addr == 192.168.1.24, dns, tcp, http) to isolate traffic.

Examined packet details:

Packet List (filtered packets)

Packet Details (protocol breakdown)

Packet Bytes (raw hex/ASCII data)

Followed TCP Stream to view the full conversation between client and server, then saved it as a .txt file.

Viewed Statistics → Protocol Hierarchy to identify protocols and their data share.

Saved the capture as .pcapng for submission.

Protocols Identified
DNS – Domain name lookups.

TCP – Reliable transport protocol for data exchange.

HTTP – Web page requests and responses.

Tools Used
Wireshark (Free, Open-Source Network Protocol Analyzer)

Outcome
Gained hands-on experience in capturing, filtering, and analyzing network traffic using Wireshark. Learned how to identify multiple protocols, follow TCP streams, and interpret raw packet data.

Repository Structure
Copy
Edit
Task5-Wireshark-Network-Traffic/
│
├── task5_capture_20250811.pcapng
├── tcp_stream1.txt
├── screenshots/
│   ├── step1_interface.png
│   ├── step2_filtered_packets.png
│   ├── step3_packet_details.png
│   ├── step4_packet_bytes.png
│   ├── step5_follow_tcp_stream.png
│   ├── step6_protocol_hierarchy.png
│
└── README.md
How to View the Capture
Download the .pcapng file from this repository.

Open it in Wireshark.

Use filters (e.g., dns, tcp, http) to explore the traffic.

