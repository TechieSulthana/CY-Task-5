# Task 5 — Capture and Analyze Network Traffic Using Wireshark  

## 📌 Objective  
Capture live network packets using Wireshark, identify basic protocols, and generate a short analysis report.  

---

## ⚙️ Steps Performed  
1. Installed **Wireshark** on my PC.  
2. Selected **Wi-Fi interface** for capturing traffic.  
3. Generated traffic by:  
   - Visiting websites  
   - Using the `ping` command  
4. Captured packets for ~1 minute.  
5. Applied filters for specific protocols:  
   - `dns`  
   - `tcp`  
   - `http`  
6. Stopped the capture and saved it as `task5_capture.pcap`.  

---

## 📊 Findings  
- **DNS** → Shows domain resolution queries (e.g., google.com).  
- **TCP** → Establishes reliable connections for data transfer.  
- **HTTP/HTTPS** → Showed browsing traffic (HTTPS is encrypted).  

---

## 📁 Deliverables  
- Packet Capture File: `task5_capture.pcap`  (private/for security)
- Report: `Task5_Report.docx` (or `.md` if uploaded)  

---

## ✅ Conclusion  
This task demonstrated how network traffic can be captured and analyzed in real time. Wireshark allowed me to visualize different protocols and understand how data flows across the network during normal activities like browsing and pinging.  
