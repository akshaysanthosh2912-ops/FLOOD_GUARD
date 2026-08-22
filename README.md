# 🌊 FLOOD GUARD

## Flood Rescue and Emergency Response System

FLOOD GUARD is a flood emergency management and rescue coordination system designed to help connect people affected by floods with rescue teams and emergency services.

The system aims to provide a fast and organized way to send emergency requests, share locations, manage rescue operations, and monitor ongoing flood-related activities.

---

## 🚨 Main Features

- Emergency SOS requests
- GPS location sharing
- Rescue request tracking
- Rescue team management
- Boat and vehicle management
- Emergency service contacts
- Weather and flood analysis
- Rescue operation monitoring
- Real-time rescue status updates
- Shelter and resource management
- Offline support
- Emergency notifications

---

## 👥 Users

The system will support different types of users:

### 🧍 Public / Victim
- Send SOS requests
- Share live location
- Provide emergency details
- Track rescue status
- Access emergency contacts and precautions

### 🚑 Rescue Team
- View assigned rescue requests
- Accept or update rescue operations
- Share location
- Update rescue status

### 🖥️ Control Room / Admin
- Monitor all emergency requests
- View rescue teams
- Assign rescue teams
- Monitor ongoing operations
- Manage resources and shelters

---

## 🛠️ Technology Stack

### Frontend
- Flutter

### Backend
- Python
- FastAPI

### Database
- PostgreSQL

### Additional Technologies
- WebSockets for real-time communication
- JWT for authentication
- GPS and Maps integration
- SQLite for offline storage
- AI/ML for future flood analysis and rescue prioritization

---

## 📂 Project Structure

```text
FLOOD_GUARD/
│
├── frontend/              # Flutter application
│
├── backend/               # FastAPI backend
│   ├── main.py
│   ├── models/
│   ├── routes/
│   ├── schemas/
│   └── database/
│
├── README.md
└── .gitignore
