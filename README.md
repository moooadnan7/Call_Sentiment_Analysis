# 📞 AI Call Analysis System

## 🧠 Overview
This project implements an **AI-powered call analysis system** that:
1. **Receives customer calls**
2. **Transcribes the audio to text** using OpenAI Whisper
3. **Analyzes the sentiment and tone** of the conversation
4. **Extracts key insights and phrases**
5. **Generates a structured report** summarizing customer mood, intent, and key discussion points

The system is designed for **call centers, sales teams, and customer service analytics**, providing valuable insights for performance improvement and customer satisfaction monitoring.

---

## 🚀 Features
- 🎧 **Automatic Speech Recognition (ASR)** using OpenAI Whisper  
- 💬 **Sentiment Analysis** on the transcribed conversation  
- 🔑 **Key Phrase Extraction** to identify important moments or customer concerns  
- 📊 **Automated Reporting** summarizing call quality and customer emotions  
- 🧩 **Modular Design** — easy to integrate with other analytics or CRM systems  

---

## 🏗️ Project Architecture
```mermaid
flowchart LR
A[📞 Incoming Call Audio] --> B[🎙️ Whisper Transcription]
B --> C[🧠 NLP Analysis - Sentiment & Key Phrases]
C --> D[📈 Structured Summary Report]
D --> E[📤 Output to Dashboard / Database]
