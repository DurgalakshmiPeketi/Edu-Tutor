# Edu-Tutor
EduTutor AI is a personalized learning platform that uses Hugging Face models to auto-generate quizzes by topic. It adapts quiz difficulty based on student performance, syncs courses via Google Classroom, and provides real-time feedback and analytics for both students and educators.
# 🎓 EduTutor AI - Personalized Learning Platform

EduTutor AI is an intelligent learning platform built with **Streamlit** that tailors educational content for students based on their diagnostic assessments. It uses AI to generate quizzes, assess performance, and adapt to the learner's skill level.

---

## 🌟 Features

- 🔐 User Authentication (Student & Educator)
- 🧠 Diagnostic Quiz to assess current knowledge level
- 🧪 AI-Powered Quiz Generation based on Topic and Difficulty
- 📊 Performance Evaluation & Feedback
- 🏆 Personalized Dashboard
- 💾 Data stored in SQLite
- 🌐 Streamlit Web UI

---

## 📁 Project Structure
EduTutor-AI/
├── streamlit_app.py # 🎯 Main Streamlit application
├── models.py # 🧠 AI Quiz generation and DB functions
├── config.py # 🔐 Configuration (OpenAI keys, DB setup)
├── requirements.txt # 📦 Python dependencies
├── .env # 🔑 Environment variables (API keys)
└── README.md # 📘 Documentation
