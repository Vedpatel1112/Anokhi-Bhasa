# Anokhi-Bhasa
🚀 ISL Translator – Real-Time Indian Sign Language to Text Converter

This project delivers a real-time translation system that converts Indian Sign Language (ISL) into textual format, helping deaf and mute individuals communicate effectively with the hearing population. It enhances inclusivity by enabling emotion-aware, AI-powered, offline-capable communication across 32+ Indian languages.

💡 Key Highlights

🔄 Two-way ISL ↔ Text Translation across Indian languages
🧠 Advanced AI algorithms (CNN, LSTM) for accurate gesture and emotion recognition
🎥 Real-time hand & face motion capture, even in low-light using low-resolution cameras
😃 Emotion sensing technology for enriched communication context
🌐 Offline compatibility for low-network or rural regions
🔒 Real-time data encryption ensures user privacy and security

🛠️ Tech Stack

Frontend: React (Web), React Native (Mobile)
Backend: Python
Libraries & Tools: TensorFlow, Keras, MediaPipe, YOLO, OpenCV, NumPy, Matplotlib
Database: MySQL (application data), Custom ISL dataset (gesture training)

📦 Our Custom Dataset
To overcome the limitations of public ISL datasets, we developed our own dataset, featuring:
10,000+ labeled ISL gestures with body and face annotations
Diverse samples across lighting, backgrounds, and regional variations
Emotion labels (happy, sad, neutral) to boost expression recognition
Our model also distinguishes similar signs (e.g., “2” vs “V”, “W” vs “3”) and evolves through a continuous AI feedback loop.

🔁 Process Architecture Overview

Capture hand & face landmarks via camera input
Segment images in HSV/YUV color spaces
Analyze gestures using CNN-based recognition
Detect non-verbal cues (facial expressions)
Map results to real-time translated output
Display results on a clean UI for mobile/web

🌍 Social Impact

📶 Empowers communication in rural and low-resource zones
👩‍💼 Creates job and learning opportunities for the deaf community
🏫 Facilitates communication in education, workplaces, and local services
🧾 Promotes digital interaction over paper-based methods
✅ Feasibility & Future Scope
✔️ Proven feasibility with real-time performance & secure offline usage
🔄 Expand dataset to cover more regional dialects
🔊 Add voice output for translated text
🧠 Further refine AI models for gesture clarity


🏆 Submitted for Smart India Hackathon (SIH) 
🥈 2nd Runner-up in SIH(Smart India Hackathon)
👥 Developed by The Tech Titans
