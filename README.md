# TASK-5-CYBER-SECURITY-INTERSHIP-
# 📡 Wireshark Packet Capture Report – Task 5

## 🎯 Objective

To **capture and analyze live network traffic** using Wireshark and identify basic protocols such as HTTP, DNS, TCP, and TLS.

---

## 🛠️ Tools Used

- **Wireshark v4.4.7**
- Active Wi-Fi Network Interface
- Web Browser (to generate live traffic)

---

## 🧪 Steps Performed

1. Installed and launched **Wireshark**.
2. Started packet capture on the **active Wi-Fi interface**.
3. Opened a browser and accessed various websites to generate real traffic.
4. Let the capture run for approximately **1 minute**.
5. Applied filters to observe key protocols:
   - `http`
   - `dns`
   - `tcp`
   - `tlsv1.2`
   - `mdns`
6. Identified **at least 3 different protocols** in the capture.
7. Exported the captured packets as a `.pcapng` file.
8. Summarized findings and key observations.

---

## 📦 Protocols Identified

| Protocol  | Description                                                                 |
|-----------|-----------------------------------------------------------------------------|
| **TCP**   | Ensures reliable communication; used to initiate encrypted sessions (e.g., port 443). |
| **TLSv1.2** | Provides encryption for application traffic (like HTTPS).                  |
| **MDNS**  | Allows device discovery on local networks without needing a DNS server.     |
| **DNS**   | Translates domain names (like `openai.com`) into IP addresses.              |
| **ARP**   | Resolves IP addresses to MAC addresses within the local subnet.             |

---

## 🖼️ Screenshots

> *(Screenshots of the Wireshark capture were taken to support the findings. You can add them here if submitting the repo.)*

---

## 📈 Outcome

This hands-on task successfully demonstrated the process of live packet capturing and **protocol identification** using Wireshark. It strengthened practical understanding of networking basics, traffic flows, and common diagnostic tools.

---

## 📁 Suggested Folder Structure

