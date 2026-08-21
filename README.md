# 🚨 PagerDuty

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-22+-339933?logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-BullMQ-DC382D?logo=redis&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Realtime-Socket.IO-010101?logo=socket.io&logoColor=white)
![Gemini](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-4285F4?logo=google&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React%20%2B%20Vite-646CFF?logo=vite&logoColor=white)

### AI-Powered Incident Response & Operations Management Platform

SignalStack is a modern incident management platform inspired by PagerDuty, built to help engineering and operations teams detect, investigate, and resolve production incidents faster through real-time collaboration, intelligent automation, and AI-assisted analysis.

</div>

---

## ✨ Key Features

- 🚨 End-to-end incident lifecycle management
- 🤖 AI-powered incident analysis using Google Gemini
- ⚡ Real-time collaboration with Socket.IO
- 📡 Monitoring-driven incident creation and alerting
- 📊 Live operational dashboards and analytics
- 🛡️ Role-Based Access Control (RBAC)
- 🧾 Complete incident timeline and audit history
- 🔄 Background job processing with BullMQ & Redis
- 📈 Severity tracking, trends, and workload insights
- 🎯 Structured AI recommendations and response playbooks

---

## 🏗️ Architecture

SignalStack follows a scalable full-stack architecture designed for reliability and real-time operational workflows.

### Frontend
- React 19
- Vite
- Redux Toolkit
- React Router
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB & Mongoose
- Redis
- BullMQ

### Realtime Layer
- Socket.IO
- Live incident feeds
- Real-time notifications
- Collaborative incident rooms

### AI Layer
- Google Gemini 2.5 Flash
- Root cause analysis
- Incident summarization
- Response recommendations
- Automated playbook generation

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|-------------|
| Frontend | React, Vite, Redux Toolkit, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Realtime | Socket.IO |
| Queue System | Redis, BullMQ |
| AI | Google Gemini 2.5 Flash |
| Validation | Zod |
| Analytics | Recharts |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 22+
- MongoDB
- Redis
- Google Gemini API Key

### Installation

```bash
# Clone Repository
git clone <repository-url>

# Backend Setup
cd Backend
npm install

# Frontend Setup
cd ../Frontend
npm install
```

### Run Backend

```bash
cd Backend
npm run dev
```

### Run Frontend

```bash
cd Frontend
npm run dev
```

Frontend: `http://localhost:5173`

Backend: `http://localhost:5000`

---
# SignalStack - Smart Incident Response Platform

## Dashboard

The real-time operations dashboard provides live incident tracking, severity analysis, and monitoring insights.

![SignalStack Dashboard](screenshorts/Screenshot 2026-08-21 at 11.22.18 AM.png.png)


## 🎯 Roadmap

- SLA Policy Management
- Escalation Policies
- On-call Scheduling
- Email & Slack Integrations
- Advanced Analytics
- OpenAPI / Swagger Documentation
- Automated Demo Data Seeding
- Comprehensive Test Coverage

---

## 🤝 Contributing

Contributions are welcome. Please create a feature branch, follow the project structure, and ensure all frontend and backend changes are properly tested before opening a pull request.

---

## 📄 License

ISC License

---

## ⭐ Support

If you find this project useful, consider giving it a star and contributing to future improvements.

**Built for modern incident response, operational excellence, and AI-assisted reliability engineering.**