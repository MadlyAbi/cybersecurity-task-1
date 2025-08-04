🛡️Task 1 – Network Port Scanning & Packet Analysis

📌Objective
To discover devices and open ports in the local network using **Nmap**, and analyze packet-level behavior of a SYN scan using Wireshark.


🛠️ Tools Used
Kali Linux
Nmap 7.95 – TCP SYN scanning
Wireshark – Packet analysis


🧪 Step 1 – Nmap TCP SYN Scan

🔍 Command Used
bash
sudo nmap -sS 192.168.x.0/24 -oN scan_result.txt

This command sends TCP SYN packets to devices on the local subnet to identify open ports without completing the full TCP handshake.
