LetsDefend – PCAP Analysis Challenge

1. Lab Overview

- Platform: LetsDefend
- Challenge: PCAP Analysis
- Category: Network Traffic Analysis
- Difficulty: Beginner
- Status: Completed

Objective

Analyze a captured network traffic file (PCAP) to investigate network communications, identify the sender and receiver, and extract information about a file uploaded to a web server.

PCAP File:
"Pcap_Analysis.pcapng"

File Location:
"/root/Desktop/ChallengeFile/Pcap_Analysis.pcapng"

---

2. Investigation & Findings

Q1 – Identify Sender and Receiver IP Addresses

Question: In network communication, what are the IP addresses of the sender and receiver?

Findings:

- Sender IP: "192.168.235.137"
- Receiver IP: "192.168.235.131"

Answer: "192.168.235.137,192.168.235.131"

Evidence:

<img width="808" height="367" alt="Screenshot 2026-11-21 154819" src="https://github.com/user-attachments/assets/13c1bf50-81c1-4163-a43b-bd6b14cf6b7b" />


---

Q2 – Identify the Web Server IP Address

Question: PI3 uploaded a file to the web server. What is the IP address of the server?

Finding:

- Web Server IP: "192.168.1.7"

Answer: "192.168.1.7"

Evidence:

<img width="837" height="328" alt="Screenshot 2026-11-21 154447" src="https://github.com/user-attachments/assets/6e84f651-cac6-43b7-80d6-006648510289" />


---

Q3 – Identify the Transferred File Name

Question: What is the name of the file that was sent through the network?

Finding:

- File Name: "file"

Answer: "file"

Evidence:

<img width="845" height="368" alt="Screenshot 2026-11-21 154434" src="https://github.com/user-attachments/assets/d8912e19-7064-48b0-909c-dd23a2c27b63" />


---

Q4 – Identify Web Server Software

Question: What is the name of the web server software where the file was uploaded?

Finding:

- Web Server Software: "Apache"

Answer: "apache"

Evidence:

<img width="799" height="399" alt="Screenshot 2026-11-21 154846" src="https://github.com/user-attachments/assets/68832178-01a7-4feb-8da4-a351991b812c" />


---

Q5 – Identify the Upload Directory

Question: What directory was the file uploaded to?

Finding:

- Upload Directory: "uploads"

Answer: "uploads"

---

Q6 – Identify the Sender Port

Question: From which port did the sender send the encrypted file?

Finding:

- Identified port information from the network traffic.

Answer: "0.0073"

Evidence:

<img width="804" height="400" alt="Screenshot 2026-11-21 154951" src="https://github.com/user-attachments/assets/d615efd4-f21a-4399-a3b5-1fc364cb19f1" />


---

3. Key Findings Summary

Investigation Item| Result
Sender IP| 192.168.235.137
Receiver IP| 192.168.235.131
Web Server IP| 192.168.1.7
Transferred File| file
Web Server Software| Apache
Upload Directory| uploads
Identified Ports| 0.0073

---

4. Skills & Knowledge Gained

- PCAP file analysis.
- Network communication investigation.
- Identifying source and destination IP addresses.
- Analyzing file transfer activity.
- Identifying web server information.
- Extracting HTTP-related artifacts.
- Investigating network ports and communication.

5. Conclusion

Successfully completed the LetsDefend PCAP Analysis challenge by examining captured network traffic and extracting relevant information about the communication between the sender, receiver, and web server.

The investigation helped strengthen practical skills in network traffic analysis and identifying file transfer activities from PCAP files.

Lab Status: Completed
