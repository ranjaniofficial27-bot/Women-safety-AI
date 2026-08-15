Women-safety-AI
Women Safety AI Surveillance System – An AI-powered prototype using YOLOv8 + OpenCV to detect harassment-like behavior in real time. Triggers Arduino buzzer alerts, saves snapshot + video evidence, and provides proactive monitoring for women’s safety.
AI-Based Smart Harassment & Violence Detection System 

From passive CCTV to proactive, on-site alert response.

Developed by ALPHA MINDS
Sri Ramakrishna College of Arts and Science for Women  
Project Leader: Kavi Bharathi P  
 Overview
Traditional CCTV systems only record incidents after they occur, leaving a critical gap in real-time response.  
This project introduces an **AI-powered safety ecosystem** that detects harassment or violence in real-time and triggers an instant on-site alarm using minimal hardware.

Key Features:
- Real-time threat detection using YOLOv8
- Face recognition and OCR for contextual evidence
- Arduino Uno + Buzzer for instant audible alerts
- Offline, low-cost, and scalable design
- Evidence storage for incident review



 The Problem
- Passive CCTV only records, no immediate action.
- Human monitoring causes fatigue and delayed detection.
- Response latency can cost critical time during emergencies.
Our Solution
A proactive alarm-driven safety ecosystem**:

1. Live Feed → Webcam captures the monitored area.  
2. AI Analysis → YOLOv8 detects threats and aggressive postures.  
3. Context Signals → Face detection + OCR add identity/context.  
4. Signal Transfer → Arduino Uno receives trigger via USB.  
5. Instant Alert→ Buzzer sounds immediately on-site.  

System Architecture
Hardware:
- Arduino Uno (central microcontroller)
- USB Cable (power + serial data link)
- Buzzer (instant audible alarm)

Software:
- Python + OpenCV (frame capture & preprocessing)
- YOLOv8 (real-time threat detection)
- Face Libraries (recognition & matching)
- Tesseract OCR (text/context extraction)
 AI Detection & Evidence
- Real-Time AI → Monitors dynamic threat indicators.  
- Face Detection → Identifies perpetrators.  
- OCR Extraction → Reads contextual identifiers.  
- Buzzer Trigger → Arduino Uno activates alarm instantly.  
- Evidence Storage → Maintains logs for incident review.  

Innovation & Feasibility
- Low-Cost→ Minimal hardware setup.  
- Offline→ No network dependency.  
- Smart Validation → Multi-frame confidence reduces false triggers.  
- Scalable → Can be deployed across campuses, classrooms, reception desks, etc.  

 Impact
- Women & Public Citizens→ Real-time protection and reassurance.  
- Educational Institutions → Digital sentry for campuses and dorms.  
- Security & Authorities → Faster response with evidence trail.  

Core Benefits:
1. Zero-lag warning workflow  
2. Proactive security model  
3. Chronological digital evidence trail  

Installation & Usage
 Prerequisites
- Python 3.8+
- Arduino IDE
- Webcam

Install dependencies
pip install -r requirements.txt

