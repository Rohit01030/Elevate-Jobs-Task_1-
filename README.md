# Elevate-Jobs-Task_1-

Local Network Security Assessment
This project demonstrates a basic network security assessment using Nmap and Wireshark to identify open ports, capture and analyze traffic, and evaluate communication between devices within a local network.

📅 Assessment Date
May 26, 2025

👤 Assessor
Rohit Kumar

🧰 Tools Used
Nmap

Wireshark v4.x

🌐 Network SSID
10.0.2.15

🔍 Task 1: Scan Your Local Network for Open Ports
🎯 Objective
To discover open ports on devices in a local network and understand potential exposure and risks.

✅ Steps Performed
Identify the IP address

bash
Copy
Edit
ifconfig
Scan the network for open ports

bash
Copy
Edit
nmap -sS 10.2.15/24
Capture packets with Wireshark

Filter traffic to focus on HTTP packets

Analyze conversations between different devices

Visualize TCP errors using I/O Graphs

🔒 Recommendations
Close unused ports on all devices via firewall or router settings.

Disable insecure services such as Telnet.

Regularly update firmware and operating systems.

Implement network segmentation to reduce exposure and enhance security.

📁 Report
For detailed findings and analysis, refer to Report.pdf.
