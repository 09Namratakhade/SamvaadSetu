# ✨ SamvaadSetu

> **AI Powered Communication and Presentation Coach**

---

## 🚀 Overview

**SamvaadSetu** is an innovative, AI-powered, web-based system designed to transform speakers into confident, self-aware, and impactful communicators.  
By analyzing both verbal and non-verbal communication in real time, SamvaadSetu provides instant, holistic, and adaptive feedback to help users elevate their speaking skills.

---

## 🎯 What Makes SamvaadSetu Unique?

- **Multimodal Integration:** Combines audio, video, and text to deliver a complete analysis of communication style.
- **Accessibility & Inclusivity:** Tailored for marginalized communities, individuals with disabilities, non-native speakers, and anyone seeking affordable, personalized coaching.
- **Scenario-Based Training:** Practice in real-world contexts like interviews, presentations, and team discussions.
- **Comprehensive Feedback:** Integrates posture tracking, speech metrics, grammar correction, emotional and sentiment analysis, and facial expression recognition.

---

## 🛠️ Tech Stack

- 🤖 **Mediapipe**: Gesture, posture, and face tracking
- 🗣️ **Deepgram STT API**: Speech-to-text transcription
- ✍️ **LanguageTool**: Grammar checks
- 🧠 **Google Gemini (LLM)**: Emotional analysis, sentiment summarization, and enhanced feedback
- 🐍 **Python & Flask**: Backend logic and web server
- 🎞️ **ffmpeg**: Video/audio processing and conversion
- 🏷️ **NLTK**: Text analysis and sentence tokenization
- 📄 **Markdown**: Displaying formatted feedback

---

## 🎉 Features

- **Speech Transcription:** Converts spoken words into text
- **Grammar Correction:** Identifies and suggests improvements for grammatical errors
- **Facial Expression Recognition:** Analyzes emotions conveyed through facial cues
- **Hand Gesture & Posture Analysis:** Evaluates body language for effectiveness
- **Sentiment Summarization:** Provides an overview of emotional tone
- **Real-Time Feedback:** On both verbal and non-verbal communication
- **Filler Word & Pause Detection:** Highlights habits and helps reduce usage
- **Scenario-Based Training:** Simulates real-life communication challenges
- **Comprehensive Reporting:** Unified feedback integrating all analysis aspects
- **Playback & Review:** Watch recordings with synchronized feedback overlays
- **Inclusivity:** Adaptive interfaces and feedback for diverse user needs

---

## 🧑‍💻 Usage Guide

1. **Start the Application**
   
   ```bash
   python app.py
   ```

2. **Access the Web Interface**
   
   - Open your browser at `http://localhost:5000`.

3. **Begin Your Session**
   
   - 🎤 Speak or present as you normally would.
   - 👀 The system tracks gestures, posture, and facial expressions.
   - 📝 Receive instant, actionable feedback on your delivery.
   - 📊 Review your performance with comprehensive, AI-generated reports.

---

## 📂 Folder Structure

```
SamvaadSetu/
├── app.py
├── requirements.txt
├── static/
│   └── (HTML/CSS/JS files)
├── templates/
│   └── (Web templates)
├── videos/
├── posture/
├── transcripts/
├── analysis/
├── reports/
├── LLM/
└── README.md
```

---

## 🔗 API Endpoints

| Endpoint           | Method | Description                          |
| ------------------ | ------ | ------------------------------------ |
| `/`                | GET    | Serves main recording interface      |
| `/save_video`      | POST   | Receives and processes recordings    |
| `/video`           | GET    | Serves latest processed video        |
| `/report`          | GET    | Returns latest posture report        |
| `/transcript`      | GET    | Returns latest speech transcript     |
| `/analysis`        | GET    | Returns latest speech analysis       |
| `/combined_report` | GET    | Returns all analysis components      |
| `/playback`        | GET    | Serves playback interface            |
| `/analyze_report`  | POST   | Triggers AI enhancement of analysis  |
| `/llm_response`    | GET    | Provides latest enhanced AI feedback |

---

## ⚙️ Installation Guide

1. **Clone the repository**
   
   ```bash
   git clone https://github.com/09Namratakhade/SamvaadSetu.git
   cd SamvaadSetu
   ```

2. **Create a virtual environment**
   
   ```bash
   python -m venv venv
   ```

3. **Activate your virtual environment**
   
   - On **Windows**:
     
     ```bash
     venv\Scripts\activate
     ```
   
   - On **Mac/Linux**:
     
     ```bash
     source venv/bin/activate
     ```

4. **Install required packages**
   
   ```bash
   pip install -r requirements.txt
   ```

---
![](https://github.com/09Namratakhade/SamvaadSetu/blob/main/images/1747319430847.jpeg) 


![](https://github.com/09Namratakhade/SamvaadSetu/blob/main/images/1747319431424.jpeg)

![](https://github.com/09Namratakhade/SamvaadSetu/blob/main/images/1747319431178.jpeg)

---

## 📈 Future Scope

- **Advanced AI Feedback:** Deeper, context-aware analysis and recommendations
- **Multilingual Support:** Feedback in multiple languages
- **VR/AR Integration:** Immersive practice environments
- **Industry Modules:** Legal, medical, technical, and more
- **Mobile App:** Practice and feedback on the go
- **API Development:** Integration with other platforms
- **Collaborative Features:** Group practice and peer feedback
---

## 📚 References
- Flask Documentation
- MediaPipe
- Deepgram
- Google Gemini
- NLTK
- LanguageTool

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).


## Author

Created by [09Namratakhade](https://github.com/09Namratakhade), [abhishekmallav](https://github.com/abhishekmallav),[PrashantTakale369](https://github.com/PrashantTakale369), [anushree612](https://github.com/anushree612)


## **Empower your voice with SamvaadSetu!** 🎤✨

Let me know if you want to add anything specific or need a section tailored further!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/namrata-k-758922226)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:namratakhade2005@gmail.com?subject=Hello%20There&body=Just%20wanted%20to%20say%20hi!)
