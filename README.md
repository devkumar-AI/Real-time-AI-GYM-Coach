# 🏋️ Real-Time AI Gym Coach

An AI-powered gym coach that tracks your exercises in real time using computer vision. The application detects body posture, counts repetitions, checks exercise form, and provides voice-based AI assistance to improve workout performance.

---

## ✨ Features

- 🎥 Real-time pose detection using webcam
- 💪 Exercise repetition counting
- ✅ Form correction and posture feedback
- 🎙️ AI Voice Assistant
- 🤖 AI Workout Assistant (Groq API)
- 📊 Live workout statistics
- 🖥️ User-friendly Streamlit interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- OpenCV
- MediaPipe
- Groq API
- Speech Recognition
- Text-to-Speech (TTS)

---

## 📂 Supported Exercises

- Push-ups
- Squats
- Lunges
- Biceps Curls
- Shoulder Press

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/devkumar-AI/Real-time-AI-GYM-Coach.git
```

Go to the project folder

```bash
cd Real-time-AI-GYM-Coach
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 🔑 Environment Variables

Create a `.env` file and add your API key:
if it is not work then try secret.toml and add your API key there:

```env
GROQ_API_KEY=your_api_key_here
```

---

## 📁 Project Structure

```
Real-time-AI-GYM-Coach/
│
├── detectors/
├── utils/
├── app.py
├── requirements.txt
├── README.md
└── assets/
```

---

## 📸 Demo

Add screenshots or a demo GIF here.

---

## 🎯 Future Improvements

- More exercise detection
- Workout history
- User authentication
- Calories burned estimation
- Personalized workout plans

---

## 👨‍💻 Author

**Dev Kumar**

GitHub: https://github.com/devkumar-AI

---

⭐ If you like this project, consider giving it a star!
