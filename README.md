# Quantum-Secure-Communication-Defence
A Flask-based secure communication system demonstrating the BB84 Quantum Key Distribution (QKD) protocol, message encryption, intrusion detection, and secure communication concepts for defence networks. Developed during my internship at Hindustan Aeronautics Limited (HAL), Engine Division.
# 🔐 Quantum Secure Communication for Defence Networks

## 📖 About the Project

**Quantum Secure Communication for Defence Networks** is a Flask-based web application developed during my internship at **Hindustan Aeronautics Limited (HAL), Engine Division**.

The project demonstrates secure communication using the **BB84 Quantum Key Distribution (QKD)** protocol. It combines quantum key generation, message encryption and decryption, intrusion detection, audit logging, and secure authentication concepts to simulate secure communication in defence environments.

> **Note:** This project is developed for educational and research purposes to demonstrate quantum cryptography concepts and secure communication techniques.


## ✨ Features

- Secure User Login
- BB84 Quantum Key Distribution (QKD) Simulation
- Message Encryption
- Message Decryption
- Sender and Receiver Communication
- Threat Detection
- Audit Log Monitoring
- Secure Database Storage
- Flask Web Interface

## 🛠️ Technologies Used

### Programming Language
- Python

### Framework
- Flask

### Database
- SQLite

### Frontend
- HTML
- CSS
- JavaScript

### Libraries
- sqlite3
- hashlib
- matplotlib

### Development Tools
- Visual Studio Code
- Git
- GitHub

## 📂 Project Structure

```
HAL/

├── static/
│   ├── script.js
│   └── style.css
│
├── templates/
│   ├── dashboard.html
│   ├── decrypt.html
│   ├── login.html
│   ├── logs.html
│   ├── receiver.html
│   ├── sender.html
│   └── threats.html
│
├── add_column.py
├── app.py
├── audit.py
├── bb84.py
├── cc.py
├── check.py
├── check_table.py
├── database.db
├── encryption.py
├── threat_detection.py
├── requirements.txt
└── README.md
```

## ⚙️ Project Workflow

1. User logs into the application.
2. The BB84 protocol generates a secure shared quantum key.
3. The sender encrypts the message.
4. The encrypted message is securely transmitted.
5. The receiver decrypts the message using the generated key.
6. Threat detection monitors suspicious activities during communication.
7. Audit logs record system events for monitoring and analysis.

## 🔒 Security Features

- BB84 Quantum Key Distribution
- Secure Shared Key Generation
- Message Encryption
- Message Decryption
- Threat Detection
- Audit Logging
- Login Monitoring
- Secure SQLite Database

## 🚀 Installation

### Clone the Repository
```bash
git clone https://github.com/Code-Manv/quantum-secure-communication-for-defence.git
```

### Navigate to the Project
```bash
cd quantum-secure-communication-for-defence
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python app.py
```
Open your browser and visit:
http://127.0.0.1:5000

## 📊 Modules

### app.py
