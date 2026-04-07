# SentinelAI
Intelligent Crowd Behavior Monitoring System

## Overview
SentinelAI is an AI-powered surveillance system designed to enhance public safety in crowded environments such as railway stations and metro terminals. The system analyzes live video feeds to detect unusual crowd behavior and assigns risk scores to identify potentially dangerous situations in real time.

Unlike traditional surveillance systems that rely on manual monitoring, SentinelAI enables proactive threat detection and faster response.

---

## Problem Statement
In large public spaces, continuous monitoring of multiple CCTV feeds is challenging for human operators. Many incidents go unnoticed until they escalate, especially in crowded areas.

There is a need for an automated system that can analyze crowd behavior and detect anomalies early to assist security personnel.

---

## Proposed Solution
SentinelAI processes video input from cameras and applies machine learning techniques to:

- Detect people in the frame
- Track movement patterns and speed
- Identify unusual or suspicious behavior
- Assign a risk score based on detected activity
- Trigger alerts when risk exceeds a threshold

This allows authorities to respond before situations become critical.

---

## Key Features

- Real-time crowd monitoring using video input
- Detection of abnormal movement patterns
- Risk scoring system (Normal, Caution, High Alert)
- Early warning alerts for suspicious activity
- Scalable system suitable for smart city infrastructure
- Dashboard for monitoring and visualization

---

## System Workflow

1. Cameras capture live video feeds  
2. AI detects and tracks individuals in the frame  
3. Movement patterns and behavior are analyzed  
4. Risk score is computed based on anomalies  
5. Alerts are generated for high-risk scenarios  

---

## Risk Scoring Logic

The system evaluates behavior using factors such as:
- Sudden rapid movement
- Crowd dispersal or running
- Repeated suspicious motion
- Irregular movement patterns

Risk levels:
- 0–3: Normal  
- 4–6: Caution  
- 7+: High Alert  

---

## Technologies Used

- Python
- OpenCV (video processing)
- PyTorch / YOLO (human detection)
- Streamlit (dashboard interface)
- Django (backend)
- MongoDB (database)

---

## Applications

- Railway stations
- Metro systems
- Airports
- Public events and gatherings
- Smart city surveillance systems

---

## Future Scope

- Integration with live CCTV networks
- Mobile alerts for security personnel
- Crowd density heatmaps
- Integration with law enforcement systems

---
