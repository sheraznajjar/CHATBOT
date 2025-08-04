# Voice-Enabled Chatbot

Created by **Sheraz Njjae**

## 🔑 Key Features
- Real-time speech-to-text conversion  
- Natural language processing (Arabic supported)  
- Audio response generation  
- Real-time communication via WebSocket  

## ⚙️ How It Works
The chatbot includes a web-based voice interface powered by Python backend services:

### 🎛 Frontend
- Responsive HTML/CSS/JS interface  
- Live text display & message history  
- Voice input with feedback

### 🧠 Backend
- `Chatbot.py`: NLP and chatbot logic  
- `RealtimeSTT_Server.py`: Speech-to-text via streaming  

## 🧩 Requirements
- Python 3.9 – 3.12  
- API Keys:  
  - ElevenLabs (Text-to-Speech)  
  - Cohere (Arabic NLP – command-r7b-arabic-02-2025)  
- Install dependencies:
  ```bash
  pip install -r requirements.txt
