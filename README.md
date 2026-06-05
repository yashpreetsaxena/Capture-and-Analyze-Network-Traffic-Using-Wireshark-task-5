Task 5: Capture and Analyze Network Traffic Using Wireshark
Objective

Capture live network traffic and identify common network protocols using Wireshark.

Tool Used
Wireshark 4.6.6
Procedure
Installed Wireshark.
Started packet capture on the Wi-Fi interface.
Generated traffic by browsing websites.
Captured packets for approximately one minute.
Applied protocol filters.
Identified DNS, TCP, and TLS protocols.
Saved the packet capture as a .pcapng file.
Protocols Identified
DNS

Domain Name System (DNS) is used to resolve domain names into IP addresses.

Example Found:

assets.msn.com
www.google.com
lh3.google.com
TCP

Transmission Control Protocol (TCP) provides reliable communication between devices.

Example Found:

Source Port: 51293
Destination Port: 443
TLSv1.2

Transport Layer Security (TLS) encrypts network communication and secures HTTPS traffic.

Example Found:

TLSv1.2 Application Data packets
Port 443 communication
Findings
DNS queries were generated while accessing websites.
TCP packets handled reliable communication.
TLS packets represented encrypted web traffic.
Multiple secure HTTPS connections were observed.
Outcome

Successfully captured and analyzed live network traffic using Wireshark and identified DNS, TCP, and TLS protocols.
