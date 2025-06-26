# 🔒 Custom File Encryption/Decryption Tool — AES-256 Secure CLI

A secure **command-line utility** built in Python for file encryption and decryption. It uses **AES-256 symmetric encryption** in CBC mode and derives cryptographic keys securely using **PBKDF2 with SHA256**. Designed for strong file-level data confidentiality, even for large files.

---

## ✨ Features

- 🔐 Encrypts files using **AES-256 in CBC mode**
- 🔑 Secure key derivation from passwords using **PBKDF2 with SHA256**
- 🧂 Generates **unique salt and IV** for every encryption operation
- 🗃️ Handles large files via **chunk-based processing**
- 🧪 Includes **robust error handling** for I/O and validation issues

---

## 💻 Technologies Used

- **Python 3.x**
- [`cryptography`](https://pypi.org/project/cryptography/) library (AES, PBKDF2, padding primitives)
- `secrets` module (built-in, for cryptographically secure randomness)

---

## 🚀 Getting Started

1.	Clone the repository (ensure encrypt_tool.py is present).
2.	Create and activate a virtual environment (as above).
3.	Install dependencies:
4.	pip install cryptography
5.	Run the tool:
6.	python encrypt_tool.py
               o	Follow the interactive prompts to encrypt or decrypt files.
