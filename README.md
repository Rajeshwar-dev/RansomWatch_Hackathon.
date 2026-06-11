# 🛡️ RansomWatch
### AI-Powered Ransomware Early Warning & Threat Detection System

RansomWatch is an AI-powered cybersecurity platform designed to detect ransomware attacks at their earliest stage before critical data is encrypted. Instead of relying only on traditional signature-based detection, the platform continuously monitors file activities, process behavior, and suspicious encryption patterns to generate real-time alerts and reduce potential damage.

> **"Detect Early. Respond Faster. Protect Smarter."**

---

# 🚀 Overview

Modern ransomware attacks can encrypt thousands of files within seconds, often bypassing traditional antivirus solutions. RansomWatch addresses this challenge by combining behavioral monitoring, honeypot (canary) files, entropy analysis, and AI-assisted threat evaluation to identify attacks before they spread across the system.

---

# ✨ Features

- 🧠 AI-Assisted Threat Detection
- 🔍 Real-Time File System Monitoring
- 🛡️ Honeypot (Canary) File Protection
- 📊 Interactive Security Dashboard
- 📈 Threat Analytics & Visualization
- ⚡ Live Process Monitoring
- 🚨 Instant Security Alerts
- 🌐 Network Kill Switch Simulation
- 🔐 Secure Authentication with Clerk
- 📋 Event Logging & Threat Reports
- 📱 Fully Responsive Modern UI
- 🎨 Premium Cybersecurity SaaS Interface

---

# 🏗️ System Architecture

```text
                          ┌─────────────────────────┐
                          │      User / Admin       │
                          │   Web Dashboard Access  │
                          └────────────┬────────────┘
                                       │
                                       ▼
                  ┌────────────────────────────────────┐
                  │      React + Vite Frontend         │
                  │ Dashboard • Alerts • Analytics     │
                  └────────────────┬───────────────────┘
                                   │
                        REST API / WebSocket
                                   │
        ┌──────────────────────────┼──────────────────────────┐
        │                          │                          │
        ▼                          ▼                          ▼
┌─────────────────┐      ┌─────────────────┐      ┌─────────────────┐
│ Authentication  │      │   Backend API   │      │   ML Service    │
│     (Clerk)     │      │  Node + Express │      │ AI Threat Model │
└─────────────────┘      └────────┬────────┘      └────────┬────────┘
                                  │                        │
                                  └──────────┬─────────────┘
                                             │
                         ┌───────────────────▼────────────────────┐
                         │      Threat Detection Engine            │
                         │                                        │
                         │ • File System Monitoring               │
                         │ • Process Behavior Analysis            │
                         │ • File Entropy Analysis                │
                         │ • Honeypot (Canary) File Detection     │
                         │ • Threat Score Calculation             │
                         └───────────────────┬────────────────────┘
                                             │
            ┌────────────────────────────────┼───────────────────────────────┐
            ▼                                ▼                               ▼
 ┌──────────────────┐              ┌──────────────────┐           ┌──────────────────┐
 │   Alert Manager  │              │ Network Kill     │           │ Activity Logger  │
 │ UI / Email Alert │              │ Switch Simulator │           │  & Event Logs    │
 └─────────┬────────┘              └────────┬─────────┘           └────────┬─────────┘
           └────────────────────────────────┼────────────────────────────────┘
                                            │
                                            ▼
                           ┌────────────────────────────────┐
                           │      PostgreSQL Database       │
                           │  Alerts • Logs • Reports •    │
                           │     Monitoring Information     │
                           └────────────────────────────────┘
```

---

# ⚙️ How It Works

### Step 1 — Continuous Monitoring
The system continuously monitors selected files, folders, and running processes for suspicious activities.

### Step 2 — Behavioral Analysis
It tracks unusual patterns such as:
- Rapid file renaming
- Mass file modifications
- Unauthorized file encryption
- Abnormal process behavior

### Step 3 — Honeypot Detection
Hidden canary files are placed inside protected directories. Any unauthorized access to these files instantly raises a security flag.

### Step 4 — AI Threat Evaluation
Behavioral data and entropy analysis are processed by the AI engine to calculate a real-time threat score.

### Step 5 — Alert & Response
If the threat score exceeds the safe threshold:
- User receives instant alerts.
- Event logs are generated.
- Network Kill Switch simulation can be triggered to isolate the system.

---

# 📊 Dashboard Modules

## 🏠 Dashboard
- System Security Overview
- Active Threat Score
- Protected Files Counter
- Live Monitoring Status
- AI Threat Evaluation

## 🚨 Alerts Center
- Real-Time Threat Notifications
- Alert Severity Levels
- Event Timeline
- Incident Details

## 📈 Threat Analytics
- Attack Trend Graphs
- Threat Distribution Charts
- File Activity Monitoring
- Historical Reports

## ⚙️ Process Monitor
- Running Process Tracking
- Suspicious Activity Detection
- CPU & Memory Usage
- Process Threat Score

## 🛡️ Canary File Manager
- Protected Honeypot Files
- Trigger Status
- File Access Timeline

## 🔧 Settings
- Monitoring Preferences
- Notification Settings
- Security Threshold Configuration
- User Profile & Authentication

---

# 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| Frontend | React.js + Vite |
| UI Framework | Tailwind CSS |
| Animation | Framer Motion |
| Backend | Node.js + Express.js |
| Authentication | Clerk |
| Database | PostgreSQL |
| AI/ML Service | Python |
| Real-Time Communication | Socket.io |
| API Documentation | Swagger/OpenAPI |
| Logging | Winston |
| Validation | Joi |
| Containerization | Docker |

---

# 📂 Project Structure

```text
code-votex/
│
├── frontend/          # React + Vite Frontend
├── backend/           # Node.js + Express API
├── ml-service/        # AI & Threat Detection Service
├── docker/            # Docker Configuration
├── .github/           # GitHub Workflows
└── README.md
```

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/sameer-sahu25/code-votex.git
cd code-votex
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

---

# 🎯 Future Scope

- 🤖 AI & Machine Learning Based Threat Classification
- 📧 Real-Time Email & Mobile Alert System
- ☁️ Cloud-Based Threat Intelligence Sharing
- 💾 Automatic File Backup & Recovery
- 🌍 Multi-Platform Support (Windows, Linux, macOS)
- 📊 Advanced Predictive Threat Analytics
- 🔗 SIEM & Enterprise Security Tool Integration
- 🛡️ Automated Incident Response & Isolation

---

# 📸 Screenshots

- 🖥️ Landing Page
- 📊 Dashboard
- 🚨 Alerts Center
- 📈 Analytics
- ⚙️ Process Monitor
- 🛡️ Canary File Manager
- 🔧 Settings

*(Add screenshots here after deployment.)*

---

# 👨‍💻 Team

**Developed by Team Code-Votex**  
🚀 Built for Cybersecurity Innovation, AI Research, and Hackathon Excellence.

---

# 📜 License

This project is intended for educational purposes, cybersecurity awareness, research, and hackathon demonstrations. Contributions and improvements are always welcome.

---

## ⭐ If you like this project, don't forget to give it a Star on GitHub!
