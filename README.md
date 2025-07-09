AI-Powered Interactive Learning Assistant with Emotion Recognition
🔗 Access the Project
👉 Click below to run the project in Google Colab:

📘 Main AI Assistant Notebook (https://colab.research.google.com/github/KPhanindraReddy/PB4_ai_classroom_assistant_Intel_Internship/blob/main/Problem_Statement_4_intel_edu_bot.ipynb)

📗 Face detection(https://colab.research.google.com/drive/1YX1nbhvvcgal4jYkjRnPZG2IrhMjov_j)

🧾 Overview
This comprehensive AI system enhances classroom engagement through multimodal interaction and real-time emotion recognition. It integrates:

Interactive Learning Assistant – AI-powered educational support with text, voice, image, and document capabilities

Emotion Recognition System – Real-time student engagement tracking using computer vision

🔑 Key Features
🧠 Interactive Learning Assistant
Multimodal Interaction

Text-based chat using Mistral-7B

Voice input via Whisper

Image understanding with InternVL

Student Analytics

Analyze performance from CSV/Excel files

Generate insights and recommendations

Automated Lesson Planning

PDF/DOCX document parsing

AI-generated lesson outlines

Visual Search

Context-based image retrieval

Uses Google Custom Search API

🎯 Emotion Recognition System
Real-Time Emotion Detection

Detects 5 emotional states: neutral, happy, sad, surprise, anger

Classifies engagement as engaged or disengaged

Computer Vision Pipeline

Face detection using ADAS model

Facial landmarks with 35-point detection

Accelerated using OpenVINO

Live Analytics Dashboard

Visual breakdown of emotional and attention states

Real-time FPS tracking and monitoring

⚙️ Technical Specifications
Component	Technology Stack
AI Models	Mistral-7B, InternVL, Whisper
Computer Vision	OpenVINO, ADAS face detection
Backend	OpenVINO, Gradio, NumPy
Frontend	Gradio UI with custom CSS
APIs	Google Custom Search JSON API

🚀 Setup Instructions
Prerequisites
A Google Colab account

A valid Google API Key (for image search)

Webcam access (for real-time emotion tracking)

Runtime Setup in Colab
Open the notebook using one of the links above

Go to Runtime → Change runtime type → Select TPU (v2-8)

Allow webcam access when prompted

If the webcam feed glitches, restart the session and re-run the cells
