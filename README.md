# 🔐 Python Account Saver

A simple, secure, and offline Python tool to save and manage all your accounts locally on your device.

---

## 📖 Table of Contents
- [About](#about)
- [Features](#features)
- [How It Works](#how-it-works)
- [Requirements](#requirements)
- [Installation](#installation)
  - [Termux](#termux)
  - [Kali Linux](#kali-linux)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Security & Privacy](#security--privacy)
- [Warnings](#warnings)
- [FAQ](#faq)
- [Project Status](#project-status)
- [License](#license)
- [Credits](#credits)

---

## 📌 About
**Python Account Saver** is a free, lightweight Python tool that allows you to store your accounts securely **offline**.  
All your data is saved locally on your device — nothing is uploaded, shared, or tracked.

This tool is made for users who want a **simple local account manager** without relying on cloud services.

---

## ✨ Features
- 🔒 Secure password hashing (bcrypt)
- 🗂 Save multiple accounts
- 💻 Works on Linux & Termux
- ⚡ Lightweight & fast
- 🌐 Fully offline
- 🧠 Easy to use CLI interface
- 📁 Local file storage only

---

## 🧠 How It Works
1. You add your account details.
2. Passwords are **hashed using bcrypt**.
3. Data is saved in a local file on your device.
4. No internet connection is required after installation.

---

## 🧰 Requirements
- Python 3.x
- Git
- Required Python libraries:
  - `requests`
  - `colorama`
  - `bcrypt`

---

## ⚙️ Installation

### 📱 Termux
```bash
pkg install python
pkg install git

git clone https://github.com/FRn13ds/acc_saver_V3
cd acc_saver_V3

pip install requests colorama bcrypt
python update.py
```

### 🐧 Kali Linux
```bash
sudo apt-get install python3
sudo apt-get install git

git clone https://github.com/FRn13ds/acc_saver_V3
cd acc_saver_V3

pip3 install requests colorama bcrypt
python3 update.py
```
▶️ Usage
```
python main.py
```
📁 Project Structure
```
acc_saver_V3/
│
├── main.py
├── update.py
├── requirements.txt
├── data/
│   └── accounts.db
├── README.md
└── utils/
    └── helpers.py
```
## ⚠️ Warnings

→ This tool is intended only for personal use

→ Do NOT use it for illegal purposes

→ Always keep backups of your data file

→ Losing the file means losing access to saved accounts



## ❓ FAQ

Is this tool safe?

→ Yes. It uses bcrypt hashing and stores everything locally.

Does it need internet?

→ Only for installing dependencies. After that, no.

Can I recover passwords?

→ No. Passwords are hashed for security.

Is this open source?

→ Yes.


## 🚫 Project Status

⚠️ THIS IS THE LAST VERSION OF THIS PROJECT
No future updates are planned.

Thank you for using Python Account Saver ❤️
