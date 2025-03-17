# HTB-Bike 🚴‍♂️ - SSTI Exploit

![HTB Bike](https://infosec-db.github.io/CyberDepot/assets/htb-bike.png)

## 🔥 Overview
**HTB-Bike** is an **SSTI (Server-Side Template Injection) exploit** for the *Bike* machine on **Hack The Box**.  
This script detects and exploits an **SSTI vulnerability** in **Node.js Handlebars** to achieve **Remote Code Execution (RCE)**.  

✅ **Automated SSTI Detection**  
✅ **SQLmap-Styled Output**  
✅ **Fancy ASCII Banner**  
✅ **JSON Debugging**  

---

## 🚀 Exploit Features

📌 **SSTI Detection** – Automatically checks if the target is vulnerable.  
📌 **Command Execution** – Runs arbitrary system commands.  
📌 **Automated Flag Retrieval** – Fetches `/root/flag.txt` on success.  
📌 **Debugging Mode** – Saves failed responses to `debug.json` for analysis.  
📌 **SQLmap-Styled Output** – Colored logs for easy readability.  

---

## 🛠️ Installation & Usage

### **1️⃣ Clone the Repo**
```bash
git clone https://github.com/yourusername/HTB-Bike.git
cd HTB-Bike
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Exploit**
```bash
python3 bike_exploit.py
```

---

## 🎯 Example Output

```plaintext
  ____  _ _      ____               
 | __ )(_) |_   |  _ \ _ __ ___  ___ 
 |  _ \| | __|  | |_) | '__/ _ \/ _ \
 | |_) | | |_   |  __/| | |  __/  __/
 |____/|_|\__|  |_|   |_|  \___|\___|

================================================================================
  Server-Side Template Injection Exploit - HTB Bike 
  Made by #AfterDark 
================================================================================
[!] DISCLAIMER: Use this tool for authorized testing only. 
    The author assumes no liability for misuse. 
================================================================================
[12:00:00] [INFO] Starting SSTI Exploit for Bike HTB Machine
[12:00:01] [SUCCESS] SSTI vulnerability detected!
[12:00:02] [INFO] Checking user privileges...
[12:00:02] [SUCCESS] Running as: root
[12:00:03] [INFO] Fetching flag...
[12:00:04] [SUCCESS] Flag: 6b258d726d287462d60c103d0142a81c
```

---

## 📜 Legal Disclaimer
This tool is for **educational purposes only**. The author assumes **no liability** for unauthorized use.  

---
💀 **Developed by:** **#AfterDark**  
🔗 More writeups: [CyberDepot](https://infosec-db.github.io/CyberDepot/)
