## 🎯 Objective: Network log analysis for threat intelligence

### 🔹 Prompt: Examine the following network log. Identify the destination IP address with the highest outbound traffic and list associated port numbers.
### Network logs: [netlogs.txt](https://github.com/user-attachments/files/20445207/netlogs.txt)

# 🧠 Network Traffic Analysis Report

## 🔍 Objective
Identify the **destination IP address with the highest outbound traffic** and list all associated **port numbers** based on the provided network logs.

---

## 📊 Step 1: Outbound Traffic Count per Destination IP

| Destination IP   | Count |
|------------------|-------|
| 186.20.20.27     | 7     |
| 176.30.30.27     | 6     |

✅ **Highest outbound traffic is to:** `186.20.20.27`

---

## 📌 Step 2: Associated Port Numbers for `186.20.20.27`

| Protocol | Port  |
|----------|-------|
| TCP      | 21    |
| TCP      | 8080  |
| UDP      | 123   |
| UDP      | 5000  |
| ICMP     | N/A   |

✅ **Associated Ports:** `21`, `8080`, `123`, `5000`  
✅ **ICMP** traffic is also observed (does not use a port number)

---

## 🛡️ Summary

- **Destination IP with highest outbound connections:** `186.20.20.27`
- **Associated Port Numbers:** `21`, `8080`, `123`, `5000` + `ICMP`

This IP exhibits high traffic across multiple protocols and ports, indicating **potential malicious behavior** such as data exfiltration, scanning, or multi-stage attacks.

---
