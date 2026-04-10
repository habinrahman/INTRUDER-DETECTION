# 🔐 AI-Powered Intruder Detection System

An intelligent security system that detects unauthorized individuals using facial recognition and sends real-time alerts with captured images. Designed for homes, offices, and surveillance environments, this project leverages computer vision and automation to enhance security.

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![AI](https://img.shields.io/badge/AI-Face%20Recognition-orange)
![Status](https://img.shields.io/badge/Status-Production--Ready-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

The **Intruder Detection System** is an AI-based surveillance solution that identifies unknown individuals through facial recognition. Upon detection, the system captures images, logs intrusion events, and sends real-time email alerts with evidence.

This project demonstrates expertise in **Computer Vision, Artificial Intelligence, Cybersecurity, and Automation**.

---

## 🚀 Features

- 🎥 Real-Time Intruder Detection using OpenCV  
- 🧠 AI-Based Facial Recognition with the `face_recognition` library  
- 📧 Instant Email Alerts with captured images  
- 📸 Automatic Image Capture of intruders  
- 🗂️ Intrusion Logging for monitoring and auditing  
- 🕵️ Face Detection with Background Blur for privacy  
- ⚡ Multi-threaded Alert System for faster performance  
- 🖥️ Optional Preview Window  
- ⏱️ Execution Time Monitoring  
- 🔧 Configurable and Modular Architecture  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| OpenCV | Image Processing and Computer Vision |
| face_recognition | AI-based Facial Recognition |
| NumPy | Numerical Computation |
| SMTP | Email Alert System |
| Threading | Asynchronous Execution |
| argparse | Command-Line Interface |
| Git & GitHub | Version Control and Collaboration |

---

## 📂 Project Structure


INTRUDER-DETECTION/
│
├── src/
│ ├── detection/
│ ├── alerts/
│ ├── database/
│ └── utils/
│
├── known_faces/
├── intruder_images/
├── logs/
├── tests/
├── docs/
│
├── main.py
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE


---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/habinrahman/INTRUDER-DETECTION.git
cd INTRUDER-DETECTION
2️⃣ Create a Virtual Environment
python -m venv venv
Activate the Environment

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
🔧 Configuration
📧 Email Configuration

Update credentials in src/alerts/send_alert.py or use environment variables:

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
ALERT_RECEIVER=receiver_email@gmail.com

For Gmail:

Enable 2-Step Verification
Generate an App Password
▶️ Usage
Run the Intruder Detection System
python main.py
Run with Preview Window
python main.py --preview
Display Execution Time
python main.py --timer
Run with Both Options
python main.py --preview --timer
🧠 How It Works
The system activates the webcam.
OpenCV captures real-time video frames.
The face_recognition library detects faces.
Unknown faces are flagged as intruders.
The intruder’s image is captured and blurred for privacy.
The system:
Saves the image locally
Logs the intrusion event
Sends an email alert with evidence
📸 Sample Output
🛡️ INTRUDER DETECTION SYSTEM ACTIVE

🔴 INTRUDER DETECTED - ACTION 🔴
[INFO] Initializing camera...
[INFO] Successfully read frame on attempt 1
🎯 Saved: intruder_images/intruder_20260410_143522_blurred.jpg
Email alert sent successfully!
📊 Future Enhancements
🌐 Web Dashboard using FastAPI or Flask
🖥️ GUI using Tkinter or PyQt
☁️ Cloud Storage Integration (AWS S3 or Firebase)
📱 Mobile Notifications via Telegram or Twilio
🐳 Docker Containerization
🔔 Sound Alerts and Motion Detection
📈 Analytics and Reporting Dashboard
🎯 AI Model Optimization for Accuracy
🧪 Testing

Run test scripts from the tests directory:

python tests/test_opencv.py
python tests/test_face_recognition.py
🔒 Security Considerations
Do not commit .env files containing credentials.
Use App Passwords instead of actual email passwords.
Store sensitive data securely.
Ensure captured images comply with privacy regulations.
🚀 Deployment Options
Platform	Purpose
GitHub	Version Control
Docker	Containerization
AWS EC2	Cloud Deployment
Raspberry Pi	Edge Surveillance
Render / Vercel	Web Interface Integration
👨‍💻 Author

Habin Rahman
🎓 Master of Computer Applications (MCA)
💼 Software Engineer | AI & Backend Developer

🌐 GitHub: https://github.com/habinrahman
📧 Email: habin936@gmail.com
💼 LinkedIn: https://www.linkedin.com/in/habinrahman
📄 License

This project is licensed under the MIT License.
See the LICENSE file for details.

🌟 Support the Project

If you found this project useful:

⭐ Star the repository
🍴 Fork it for improvements
📢 Share it with others