<div align="center">

# 🅿️ KIIT ParkEase
### AI-Powered Smart Parking Management System

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat)

### 🏆 Selected for Faculty Research Publication — Feb 2026

</div>

---

## 🚀 Live API
http://15.206.93.167:8000
http://15.206.93.167:8000/docs

## ✨ Features
- 🤖 YOLOv8 vehicle detection on 400+ annotated images
- 🅿️ 150+ parking slots across 6+ campus locations
- ☁️ AWS EC2 deployment (Mumbai region)
- 📸 AWS S3 image storage
- ⚡ Redis caching layer
- 📊 CloudWatch monitoring
- 🔐 Role-based access control (RBAC)
- 📲 Real-time slot reservation system
- 🗺️ Leaflet.js interactive map
- 📧 Email + SMS notifications

## 🏗️ Architecture
Camera/Image Upload
↓
AWS S3 Storage
↓
YOLOv8 Vehicle Detection
↓
FastAPI Backend on AWS EC2
↓
Redis Cache Layer
↓
CloudWatch Monitoring
↓
Frontend Dashboard (Leaflet Map)

## 📁 Project Structure
KIIT-ParkEase/
├── backend/
│   ├── app.py           # Main FastAPI application
│   ├── main.py          # Entry point
│   ├── fast_main.py     # Fast API routes
│   ├── simulate.py      # Parking simulation
│   └── create_user.py   # User management & RBAC
├── frontend/
│   ├── index.html       # Landing page
│   ├── home.html        # Main dashboard
│   ├── admin.html       # Admin panel
│   ├── user.html        # User portal
│   └── login.html       # Authentication
├── .env.example
├── .gitignore
└── README.md

## ⚙️ Installation

```bash
git clone https://github.com/Aditidixit1234/Parkease.git
cd Parkease
pip install -r requirements.txt
cp .env.example .env
cd backend
uvicorn app:app --reload
```

## 📊 Results
| Metric | Value |
|---|---|
| Detection Speed | < 200ms |
| Parking Slots | 150+ |
| Campus Locations | 6+ |
| Training Images | 400+ annotated |

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| AI/ML | YOLOv8, Custom Dataset |
| Backend | FastAPI, Python |
| Cloud | AWS EC2, S3, CloudWatch |
| Cache | Redis |
| Frontend | HTML, CSS, JS, Leaflet.js |
| Auth | RBAC, Session Handling |

## 🔮 Roadmap
- [ ] Mobile app
- [ ] Payment gateway
- [ ] Multi-campus support
- [ ] Real-time camera feeds

## 👩‍💻 Author
**Aditi Dixit**
[![GitHub](https://img.shields.io/badge/GitHub-Aditidixit1234-181717?style=flat&logo=github)](https://github.com/Aditidixit1234)

---
<div align="center">
⭐ Star this repo if you found it helpful!
🏆 Selected for Faculty Research Publication — KIIT University, Feb 2026
</div>


