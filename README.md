# LAB 9 Network-traffic-capture-and-analysis-with-Wireshark
### Reg no:212223040218
### Name:SUSINDHAR K M
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:

- Captured Packets with Protocol Analysis and Detailed Packet Info

![image](https://github.com/user-attachments/assets/04a96045-99de-46fa-ac96-3a2a1a9d42a0)


- **Start Capturing Packets**

• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.

![image](https://github.com/user-attachments/assets/149ba846-3eca-4ee6-aa4b-e40beeef179b)


- **Apply Filters to Focus on Specific Traffic**
  
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

![image](https://github.com/user-attachments/assets/62defc19-5a17-4ea7-8448-274b97824fed)


- **Analyze Packet Details**
  
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.

![image](https://github.com/user-attachments/assets/9daf6d0b-ec75-4949-8a24-31f5019e3299)


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
