# ⚡ Plutus BTC Bit Scanner

**Plutus BTC Bit Scanner** is a powerful Python-based tool designed to scan the Bitcoin keyspace by generating and testing private keys in specified bit ranges. The tool checks each derived address against a local database of inactive BTC wallets that have had confirmed balances in the past.

It uses intelligent jumping within the keyspace to increase scanning efficiency and supports both compressed and uncompressed Bitcoin address formats.

---

🔐 **Package Information**

This package includes **one of two powerful tools** from the Plutus suite, specifically focused on private key bitspace scanning.

> ⚠️ Please note:  
Each password is **linked to your IP and device**.  
If you use a VPN or change your IP, the password will no longer be valid.  
This is a security measure to ensure each license is used fairly and not abused.

---

✅ **Features**

- 🔐 Remote Password Authentication — Verifies access securely via device fingerprint
- 🧠 Randomized Private Key Generator — Uses efficient key jumping
- 💻 Bit-Range Selection — You define the scan range (from 0 to 256 bits)
- 🏦 Local Database Matching — Uses `addresses11.db` to identify inactive wallets with past balances
- 💾 Logs All Hits — Saves all successful private key matches to `BTCfound.txt`
- 🧮 Supports BIP44, BIP49, BIP84 — Both compressed and uncompressed
- ⚙️ Multiprocessing — Uses all available CPU cores for faster scanning
- 📉 Memory Efficient — Monitors RAM and prints real-time stats
- 🔁 Endless Scanning Loop — Designed for long-term automated key searching

---

💡 **How It Works**

1. Launch the executable `.exe` file.
2. Enter your license password when prompted.
3. Choose your bit range (e.g. 0–10 for fast demo, or 128–256 for real scanning).
4. The script generates private keys within that range using a randomized jumping algorithm.
5. Each derived address (BIP44, BIP49, BIP84) is checked against the local database.
6. Any address with past balance is logged to `BTCfound.txt`.

---

✅ **This application does not require any additional installations.**  
Just run the `.exe` file – it works completely out of the box.  
You do **not** need Python, pip, or any external libraries.

---

🔐 **To obtain your access password, contact:**

📧 Email: **hacker001ethical@proton.me**

💵 Access Cost: **$100** — paid **only in Bitcoin (BTC)**  
📬 BTC Payment Address: `bc1qc73kzgzwtn9r6hy24dq0r6c20zxqucw25s4n2p`  
💬 You will receive a reply within **1 hour** after payment.

---

⚠️ **Legal Disclaimer**

This software is provided strictly for **educational and ethical testing purposes**.  
The developer does **not condone** or support any form of illegal activity.  
You alone are responsible for how you use this software.

---

📃 **License**

This project is licensed under the **MIT License**. See `LICENSE` for more information.
