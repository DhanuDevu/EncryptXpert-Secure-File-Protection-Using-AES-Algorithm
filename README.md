# 🔐 EncryptXpert – Secure File Protection Using AES Algorithm

EncryptXpert is a cross-platform file encryption and decryption tool built using Python, PyCryptodome, and PyQt5.
It allows users to securely protect any file using industry-standard AES encryption modes such as AES-EAX and AES-GCM.
The tool provides both a Graphical User Interface (GUI) and a Command-Line Interface (CLI), making it suitable for both beginners and advanced users.

## ⭐ Features

AES-EAX and AES-GCM authenticated encryption

Supports 128-bit, 192-bit, and 256-bit keys

Automatic nonce generation for secure encryption

Clean & modern PyQt5 GUI

CLI support for automation and scripting

Key + Nonce validation for secure decryption

Optional Key Database System

Cross-platform (Windows, Linux, macOS)

Clear logs for encryption/decryption operations

Project Architecture

EncryptXpert/
 ├── EncryptXpert.py       # Main GUI application
 ├── encryption_module.py  # AES encryption logic
 ├── decryption_module.py  # AES decryption logic
 ├── key_manager.py        # Key/Nonce database handler
 ├── requirements.txt      # Required Python packages
 └── /images               # Screenshots

 ## ⚙️ Technical Stack

Python 3.9+

PyQt5 → GUI

PyCryptodome → AES Encryption/Decryption

psutil / File handlers → File operations


Step 1 — Clone the Repository

If Git is installed:

git clone https://github.com/<your-username>/<repo-name>

If Git is NOT installed → Download ZIP:

Click Code → Download ZIP

Extract the folder

Step 2 — Open the Project Folder
cd EncryptXpert

Step 3 — Create Virtual Environment
python -m venv venv

Step 4 — Activate Virtual Environment
Windows
venv\Scripts\activate

Linux / macOS
source venv/bin/activate

Step 5 — Install Dependencies
pip install --upgrade pip
pip install -r requirements.txt

▶️ Running the Application
GUI Mode
python EncryptXpert.py


✔️ Encrypt a File

Click Load File(s)

Enter a key in Key (B) (text key)

Select key size → 128/256 bits

Click Encrypt

Note down:

Generated Key (Hex)

Generated Nonce

Your encrypted file will end with .encex

✔️ Decrypt a File

Load the .encex encrypted file

Enter:

Key (H) → hex format of your key

Nonce → the one generated during encryption

Click Decrypt

## 🧠 Architecture Overview

Frontend: PyQt5 GUI
Backend: Python + PyCryptodome
Encryption Engine: AES-EAX / AES-GCM
Key Store (optional): Local DB for storing key–nonce pairs

## 📄 License

This project is licensed under MIT License — free to use, modify, and distribute.

## 🎉 Credits

Developed by Dhanush H. N
<br>
Guided by Mrs. Vidya H. A




