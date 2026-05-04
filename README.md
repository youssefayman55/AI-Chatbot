# 🎙️ Voice Assistant ChatBot using Speech Recognition & Text-to-Speech

## 🧠 Overview

This project is a **voice-based AI chatbot** that can listen to user speech, process it, and respond using synthesized voice.
It combines **speech recognition** and **text-to-speech (TTS)** to create a simple interactive assistant.

The chatbot can answer predefined questions related to **AI, Machine Learning, Data Science**, and general conversation.

---

## 🚀 Features

* 🎤 Voice input using microphone
* 🧠 Speech-to-text conversion (Google Speech Recognition)
* 🔊 Text-to-speech responses
* 💬 Predefined intelligent responses (AI, ML, Data Science topics)
* 🔁 Continuous conversation loop
* ❌ Exit command to stop the assistant

---

## 🛠️ Technologies Used

* Python 🐍
* SpeechRecognition (Speech-to-Text)
* Pyttsx3 (Text-to-Speech)
* PyAudio (Microphone Access)

---

## 📂 Project Structure

```id="k8m2vx"
├── app.py
└── README.md
```

---

## ▶️ How to Run

### 1. Install Dependencies

```bash id="p3z9lw"
pip install SpeechRecognition pyttsx3 pyaudio
```

> ⚠️ Note: Installing `pyaudio` may require additional setup depending on your system.

### 2. Run the Application

```bash id="q7x4rt"
python app.py
```

---

## 🎯 How It Works

* The system listens to the user's voice عبر الميكروفون
* Converts speech to text باستخدام Google Speech Recognition
* Matches the input with predefined responses
* Responds باستخدام text-to-speech (voice output)
* Continues interaction until the user says **"exit"**

---

## 🧠 Supported Topics

The chatbot can answer questions about:

* Artificial Intelligence (AI)
* Machine Learning & Deep Learning
* Data Science & Data Analysis
* Algorithms (SVM, CNN, KNN, etc.)
* General conversation (greetings, help, etc.)

---

## 📸 Example Interaction

```id="j2w6np"
You: What is machine learning?
ChatBot: Machine learning is a subset of AI that involves training algorithms to learn from data.

You: exit
ChatBot: Goodbye! Take care.
```

---

## 💡 Future Improvements

* Integrate with advanced AI models (like GPT) 🤖
* Add GUI interface (Tkinter / Streamlit)
* Support multiple languages 🌍
* Improve conversation understanding (NLP)
* Connect with external APIs for real-time answers

---

## 👨‍💻 Author

**Youssef Ayman**
AI Engineer & Data Scientist

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
