# Plutus-BTC-Toolkit-Advanced-Bitcoin-Wallet-Scanner-Suite
Link for youtube:https://youtu.be/9DyW-0Wz8gw
LINK for PlutusBTCBitScanner(SOON ! loading !)
 LINK for BTCSeedScanner (SOON! Loading !)

🔐 Plutus BTC Toolkit — Advanced Bitcoin Wallet Scanner Suite
Welcome to Plutus BTC Toolkit – a powerful, dual-program suite built for ethical researchers, penetration testers, and Bitcoin forensic analysts. This package includes two advanced scanning tools capable of identifying inactive Bitcoin wallets with past balances.

🚨These Tools search only for unused, abandoned, lost !   
🔑Only wallets with a confirmed balance or past activity !

Plutus helps you explore the Bitcoin keyspace in two intelligent ways:

🧠 Plutus BTC Seed Scanner — Scans using BIP39 mnemonic seed phrases

⚙️ Plutus BTC Bit Scanner — Scans by generating private keys directly from a defined bit range

Each tool uses a local BTC address database and advanced algorithms to check against known addresses that have held balances in the past.

🧩 Included Tools
1. Plutus BTC Seed Scanner
🔍 “Word-based scanning using seed phrases”

This tool generates random 12- or 24-word BIP39 seed phrases and derives addresses using:

✅ BIP44

✅ BIP49

✅ BIP84

Each generated wallet is matched against a local SQLite database (addresses1111.db). If a match is found, the wallet details and private keys are logged for further investigation.

Ideal for those exploring mnemonic-based wallet generation.

2. Plutus BTC Bit Scanner
🧠 “Raw private key brute-forcing within a user-defined range”

This tool generates raw Bitcoin private keys in a custom bit range (e.g., from 2^0 to 2^256) using a randomized jumping algorithm for efficient keyspace traversal.

It supports both compressed and uncompressed address types (BIP44, BIP49, BIP84) and checks them against the database (addresses11.db).

Perfect for low-level experimentation or large-scale brute-force simulation.

✅ Features
🔐 Remote Password Verification – Ensures that access is licensed and secured by device fingerprint

🧠 BIP39 & Private Key Scanning – Choose between mnemonic seeds or private keys

💽 Local Database Matching – Matches addresses against large SQLite address sets

⚙️ Multi-Process Support – Uses all available CPU cores for rapid scanning

💾 Duplicate Prevention – Tracks previously scanned seeds to avoid repeats

🚀 No Installation Needed – Run as an .exe file without requiring Python or dependencies

🧮 Full BIP Format Coverage – Supports BIP44, BIP49, BIP84 across both scanning methods

🔁 Continuous Looping – Set and forget — ideal for long-term passive scanning

📂 File Overview
File/Folder	Description
PlutusSeedScanner.py	BIP39 Seed Phrase Scanner (mnemonic-based)
PlutusBitScanner.py	Private Key Bit Scanner (bit-range-based)
addresses11.db	Database of BTC addresses with past balances
generated_seeds.db	Tracks already scanned seed phrases
english.txt	Wordlist used for seed generation
BTCfound.txt / znalezioneBTC.txt	Output logs of found addresses
🔐 Access & License
Each copy of Plutus requires an access password.

⚠️ Passwords are bound to your IP and device.
If you use a VPN or change IP after activation, the password will no longer work.

📧 Contact for password: hacker001ethical@proton.me
💵 Cost: $100 (paid in Bitcoin only)
💰 BTC Address: bc1qc73kzgzwtn9r6hy24dq0r6c20zxqucw25s4n2p
⏱️ Response time: within 1 hour after payment confirmation

❗ Legal Notice
This software is provided for educational, ethical hacking, and research purposes only.
Any misuse of this software is strictly discouraged.

You are solely responsible for your actions.

📃 License
This project is licensed under the MIT License.
You're free to use, modify, and distribute it under the terms of that license.

Youtube presentation: available soon !
