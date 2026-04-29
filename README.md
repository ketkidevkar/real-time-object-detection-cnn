# Real Time Object Detection Using CNN

## Overview

Real Time Object Detection Using CNN is an intelligent surveillance and monitoring system designed to detect objects, identify potential threats, and provide real-time situational awareness through live video streams.

The project combines deep learning, computer vision, and a responsive web dashboard to monitor environments such as campuses, offices, transport hubs, malls, and public spaces.

This system is built with a scalable backend architecture and a modern frontend dashboard for operational visibility.

---

## Key Features

### Real-Time Detection
- Detects objects from live camera feeds and recorded video streams.
- Processes frames with optimized deep learning models for fast response.

### Threat & Hazard Monitoring
- Weapon detection module for suspicious object identification.
- Fire detection module for emergency alerting.
- Crowd risk analysis for overcrowding and density monitoring.

### Smart Dashboard
- Centralized monitoring interface for multiple camera streams.
- Alerts panel for incidents and warnings.
- Camera management and control system.
- Live analytics and operational insights.

### Alerting System
- Event logging and history tracking.
- Notification integration (Telegram-ready architecture).
- Incident escalation support.

---

## Technology Stack

### Backend
- Python
- Flask
- OpenCV
- CNN / YOLO-based Detection Models
- NumPy
- Pandas

### Frontend
- React
- Vite
- JavaScript
- CSS

### Utilities
- Logging System
- Camera Stream Manager
- Alert Store

---

## Project Architecture

Frontend Dashboard (React)  
↓  
REST/API Layer  
↓  
Python Backend (Flask)  
↓  
Detection Engine (CNN / YOLO / OpenCV)  
↓  
Camera Streams / Video Sources

---

## Repository Structure

Real-Time-Object-Detection-Using-CNN/  
│── Backend/  
│   ├── app.py  
│   └── utils/  
│── Dashboard/  
│   ├── public/  
│   └── src/  
│── Streams/  
│── detector.py  
│── tracker.py  
│── weapon_detector.py  
│── fire_detector.py  
│── crowd_risk_analyzer.py  
│── analytics.py  
│── requirements.txt

---

## Installation & Setup

### Backend Setup

pip install -r requirements.txt  
python app.py

### Frontend Setup

cd Dashboard  
npm install  
npm run dev

---

## Business Use Cases

- Smart City Surveillance
- College / Campus Security
- Railway & Metro Monitoring
- Mall & Airport Safety
- Industrial Hazard Detection
- Restricted Area Monitoring

---

## Future Enhancements

- Face Recognition Integration
- Cloud Deployment
- Mobile Notifications
- Predictive Risk Analytics
- Multi-location Monitoring
- Role-based Admin Access

---

## Academic / Portfolio Note

This project demonstrates practical implementation of AI, computer vision, full-stack integration, and real-time monitoring systems suitable for academic research and industry showcase.

---

## Author

Ketki Devkar
