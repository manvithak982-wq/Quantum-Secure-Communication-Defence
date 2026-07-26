# Quantum-Secure-Communication-Defence
A Flask-based secure communication system demonstrating the BB84 Quantum Key Distribution (QKD) protocol, message encryption, intrusion detection, and secure communication concepts for defence networks. Developed during my internship at Hindustan Aeronautics Limited (HAL), Engine Division.
# 🔐 Quantum Secure Communication for Defence Networks

## 📖 About the Project

**Quantum Secure Communication for Defence Networks** is a Flask-based web application developed during my internship at **Hindustan Aeronautics Limited (HAL), Engine Division**.

The project demonstrates secure communication using the **BB84 Quantum Key Distribution (QKD)** protocol. It integrates quantum key generation, encryption, decryption, user authentication, audit logging, and threat detection to simulate secure communication for defence environments.

The application provides role-based login for different users and monitors communication activities to identify suspicious behaviour while ensuring secure message exchange.

> **Note:** This project is developed for educational and demonstration purposes to showcase quantum cryptography concepts and secure communication techniques.

# ✨ Features
- Secure User Authentication
- Role-Based Login System
- Administrator Dashboard
- Commander Access
- Field Officer Access
- Security Analyst Access
- BB84 Quantum Key Distribution (QKD) Simulation
- Secure Shared Key Generation
- Message Encryption
- Message Decryption
- Sender and Receiver Communication
- Threat Detection
- Audit Log Monitoring
- Secure SQLite Database
- Flask-Based Web Interface

# 🛠️ Technologies Used

## Programming Language
- Python
## Framework
- Flask
## Frontend
- HTML5
- CSS3
- JavaScript
## Database
- SQLite
## Python Libraries
- Flask
- sqlite3
- hashlib
- matplotlib
## Development Tools
- Visual Studio Code
- Git
- GitHub

# 📂 Project Structure

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

# ⚙️ Project Workflow
1. User logs in using a predefined role-based account.
2. The system authenticates the user credentials.
3. The BB84 protocol generates a secure shared quantum key.
4. The sender encrypts the message using the generated key.
5. The encrypted message is securely transmitted.
6. The receiver decrypts the message using the same shared key.
7. The threat detection module monitors suspicious activities.
8. Audit logs record important system events.
9. The dashboard displays communication status, logs, and detected threats.

# 🔑 Default Login Credentials
The application includes predefined user accounts for demonstration and testing purposes.
| Username | Password | Role |
|----------|----------|------------------|
| `admin` | `admin123` | Administrator |
| `commander01` | `cmd123` | Commander |
| `officer01` | `off123` | Field Officer |
| `analyst01` | `ana123` | Security Analyst |

> **Note:** These credentials are intended only for demonstration and academic purposes.


# 🔒 Security Features

- BB84 Quantum Key Distribution
- Secure Shared Key Generation
- Message Encryption
- Message Decryption
- User Authentication
- Role-Based Access Control
- Threat Detection
- Audit Logging
- Login Monitoring
- Secure Database Storage

# 🚀 Installation

## Clone the Repository
```bash
git clone https://github.com/Code-Manv/quantum-secure-communication-for-defence.git
```

## Navigate to the Project Folder
```bash
cd quantum-secure-communication-for-defence
```

## Install Dependencies
```bash
pip install -r requirements.txt
```

## Run the Application
bash
python app.py

Open your browser and visit:
http://127.0.0.1:5000

# 📊 Project Modules
## app.py
Acts as the main Flask application and integrates all modules, routes, and web pages.
## bb84.py
Implements the BB84 Quantum Key Distribution protocol to generate secure shared keys.
## encryption.py
Encrypts and decrypts messages using the generated shared key.
## threat_detection.py
Monitors communication activities and detects suspicious behaviour or security threats.
## audit.py
Maintains audit logs of user activities and system events.
## database.db
Stores user credentials, communication records, and system logs using SQLite.
## templates/
Contains all HTML pages including:
- Login
- Dashboard
- Sender
- Receiver
- Message Decryption
- Threat Monitoring
- Audit Logs
## static/
Contains CSS and JavaScript files used for the user interface.

# 🎯 Learning Outcomes
Through this project, I gained practical experience in:
- Quantum Cryptography
- BB84 Quantum Key Distribution
- Secure Communication Principles
- Flask Web Development
- Python Programming
- SQLite Database Management
- Encryption and Decryption
- Threat Detection
- Audit Logging
- Full-Stack Web Application Development

# 📈 Future Enhancements
- Integration with Real Quantum Communication Hardware
- Multi-User Secure Communication
- Cloud Deployment
- Advanced Threat Analytics
- AI-Based Threat Detection
- End-to-End Secure Messaging
- Enhanced Authentication Mechanisms
- Improved User Interface

# 👩‍💻 Author
**Manvitha K**
B.Tech Computer Science Engineering Student
Internship Project – Hindustan Aeronautics Limited (HAL), Engine Division


This project was developed during my internship at **Hindustan Aeronautics Limited (HAL), Engine Division** as an educational and demonstration project. It showcases the concepts of **Quantum Cryptography**, **BB84 Quantum Key Distribution**, **secure communication**, **encryption**, **threat detection**, and **audit logging**. It is intended for academic learning and demonstration purposes and is not a production-ready defence communication system.
