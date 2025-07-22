# Network-Traffic-Analysis-with-Wireshark

Network traffic analysis involves monitoring and examining data packets that flow through a network to understand its behavior, identify issues, and enhance security. Wireshark is a powerful and free tool used for this purpose.

## Objective

Network traffic analysis project involved capturing and analyzing network traffic using Wireshark to evaluate network behavior, identify potential performance issues, and detect any abnormal or suspicious activity. The goal was to gain practical experience in traffic capture, protocol analysis, and threat detection, while also understanding network behavior in a real-world environment..

### Skills Learned

-  Skilled in live monitoring and quick interpretation of network traffic..
-  Ability to identify and resolve network issues such as delays and connectivity failures.
-  Improved ability to spot unusual or malicious traffic behavior
-  Built experience in analyzing traffic in various environments (LAN, wireless, virtual networks).
-  Proficient in Wireshark’s features such as filters, color rules, and statistics panels.


### Tools Used

*** Primary Tool: Wireshark (Version 4.0.3)

*** Operating System: Linux6.1.0-kali5-amd64

*** Traffic Sources: Browsing, background applications

*** Capture Duration: 10 minutes

*** Date/Time of Capture: July 21,2025, 23:00-23:10

*** Network Interface : Ethernet 0

### Steps

Below are the key steps taken in the Packet Capturing and Analysis process:

### 1. Start capturing:

Click on network interface to start capturing traffic. You will see packets being listed in real-time

1.1 Generate traffic:

To see some traffic, open a web browser and visit www.google.com. This will generate HTTP/HTTPS traffic that Wireshark will capture

*Ref 1. Generate Traffic Result*

This screenshot shows the result of generating traffic while visiting a website

 [Generate Filter](https://github.com/Maffypeterp/Network-Traffic-Analysis-with-Wireshark/blob/main/Screenshot%202025-07-22%20045521.png)

1.2 Stop Capture:

Click the red button to stop the capture after you have collected enough data.

*Ref 2. Capture Result*

This screenshot shows the result of packet capturing traffic

[Capture Traffic](https://github.com/Maffypeterp/Network-Traffic-Analysis-with-Wireshark/blob/b621087ce1bf84deefe205753dc1bf5d2ff9706b/Screenshot%202025-07-22%20045617.png) 

### 2. Analyze Network Traffic

2.1 View Packet Details:

Click on a packet in the captured traffic list to view its details. The details pane below will show the packets headers and payload.

2.2 Filter Traffic:

Use display filters to focus on specific types. Enter a filter expressions such as http, tcp, ip.addr == 10.0.2.15, tcp.port == 80 in a filter bar and press Enter.

*Ref 3. Filter Traffic Result*

This screenshot shows the result of filtering traffic using display filters

[Filter Traffic](https://github.com/Maffypeterp/Network-Traffic-Analysis-with-Wireshark/blob/main/Screenshot%202025-07-22%20050653.png)

2.3 Follow TCP/UDP Streams:

Right-click on a packet and select 'Follow'-> 'TCP Stream' or 'UDP Stream' to see the entire conversation.

2.4 Inspect Packet Contents:

Expand the packet details to inspect the headers and payload of each layer(Ethernet,IP,TCP,HTTP,etc).

2.5 Create Custom Filters:

To create custom filters using Wireshark filtering language. Combine expressions to narrow down the traffic you are interested in.

### 3. Reporting

Finally, all findings were documented, including detailed description of capturing network traffic

[Report][Link]
