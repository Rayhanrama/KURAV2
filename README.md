# 🌏 KURA AI

**KURA AI** is an AI-powered multilingual communication platform focused on preserving and enabling Southeast Asian regional languages through translation, speech interaction, and cultural exploration.

Built for hackathon use with emphasis on accessibility, low-resource language support, and cultural preservation.

---

## 🔴 Demo Video
https://youtu.be/C101BjyOyhQ

---

## ✨ Key Features

### 1. AI Language Chatbot
- Ask questions about Southeast Asian languages
- Answers generated in structured bullet-point format
- Designed for fast reading and clarity

---

### 2. Two-Way Communication
- Real-time translation between languages
- Single smart voice button (input → translate → output)
- Supports:
  - Text output
  - Voice output (Text-to-Speech)
- Includes:
  - Copy text feature
  - Voice replay translation

---

### 3. Regional Language Map (SEA Map)
- Interactive Southeast Asia map
- Each country shows local language greetings
- Click to hear pronunciation and explore languages

---

### 4. Dictionary Feature
- 24 Southeast Asian languages database
- Includes:
  - Native script
  - Romanization
  - English meaning
- Searchable vocabulary system

---

### 5. Quick Speak (Template Mode)
- Pre-save common phrases
- Instant translation + speech output
- Useful for travelers, students, and field workers

---

### 6. Quiz Feature
- Language learning gamification
- Covers all 24 regional languages
- Helps users learn through repetition and testing

---

### 7. 🔊 Suara Leluhur (Ancestral Voice Feature)
- Cultural preservation-based voice feature
- Converts traditional expressions, greetings, and folklore phrases into speech
- Designed to preserve cultural identity through audio experience
- Focuses on:
  - Oral traditions
  - Indigenous expressions
  - Cultural storytelling tone
- Bridges modern AI with heritage language preservation

---

## 🧠 Tech Stack

### Frontend
- React 18
- Vite
- TailwindCSS (clean UI system)

### Backend
- FastAPI
- Python

### AI & APIs
- Groq (Whisper / LLM inference)
- Arcee AI via OpenRouter
- Hugging Face Models (extended language support)
- Google Text-to-Speech (gTTS)

---

## 🤖 AI Disclosure

KURA AI integrates multiple AI systems:

- **Groq API**
  - Speech-to-text (Whisper)
  - Low-latency inference engine

- **Arcee AI (OpenRouter)**
  - Language reasoning model
  - Regional language contextual responses

- **Hugging Face**
  - Additional NLP support for low-resource languages

- **gTTS**
  - Text-to-speech voice generation

### Human Contribution
- System architecture
- UI/UX design
- Language dataset structuring
- Feature design & integration logic

---

## 🔐 Privacy Design
- No user data storage
- No conversation history saved
- Voice processed in real-time only

---

## 🚀 How to Run Locally

### 1. Clone Repository
```bash
git clone https://github.com/USERNAME/KURA_AI.git
cd KURA_AI