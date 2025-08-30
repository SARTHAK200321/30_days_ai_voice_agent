# 🎙️ NOVA - AI VOICE AGENT

## Project Overview:

This project was developed as part of the 30 Days of AI Voice Agents Challenge by Murf AI.
It is a conversational voice agent capable of handling speech-to-text, text-to-speech, intelligent task execution, and real-time search through various API integrations.

The system allows users to record their voice, get transcriptions, interact with a conversational agent, browse live search results, and listen to AI-generated audio replies.

## 🚀 Features Implemented:

 * Text-to-Speech (TTS) using Murf API.
 * Speech-to-Text (STT) transcription using AssemblyAI API.
 * Conversational Agent powered by Google Gemini API.
 * Weather Skill – fetches live weather updates.
 * News Skill – retrieves latest headlines by category (politics, sports, tech, etc.)
 * Browse Search – integrated SerpAPI for real-time web search and latest information.
 * API Key Configuration – users can securely enter their own API keys via the UI and use the agent with their credentials.
 * Frontend Enhancements – responsive UI with HTML, CSS, JavaScript.
 * Backend Server implemented with FastAPI (Python).

## 🛠️ Tech Stack:

### Frontend:

* HTML5
* CSS3
* JavaScript 

### Backend:

* FastAPI (Python)

### APIs & AI Models:

* Murf API (Text-to-Speech)
* AssemblyAI API (Speech-to-Text)
* Google Gemini API (Conversational AI)
* SerpAPI (Browse Search)


## 📂 Project Structure:


├── main.py            # FastAPI backend
├── static/            # Frontend assets (JS, CSS)
│   ├── script.js
├── templates/         # HTML templates
│   ├── index.html
├── requirements.txt      # Dependencies
├── schemas.py         # Data models
├── README.md          # Documentation 

## 🚀 Getting Started:

### 1.Install Dependencies
'pip install -r requirements.txt'

### 2.Run the server
uvicorn main:app --reload

### 3.Open the application in your browser http://localhost:8000


### 4.Configure API Keys
In the UI, click the ⚙️ API Key Configuration button.
Enter your keys for:
 * Murf API
 * AssemblyAI API
 * Gemini API 
 * Serp API
Save them — now the agent will use your keys for all tasks 🎉



## 🔧 How It Works

* 🎤 Start Speaking → Click the Start button to begin recording your voice.
* ⚙️ Processing → The voice data is sent to the AI backend for speech-to-text transcription and intent analysis.
* 💬 Response Generation → The AI agent uses APIs (Gemini, Weather, News, SerpAPI, etc.) to generate the correct response.
* 🔊 Playback → The reply is converted into speech (TTS via Murf API) and played back to the user.
* ❌ Error Handling → If no voice is detected, or an API key is missing, or a network issue occurs, the system displays a friendly error message.

## Example Use Cases

* What’s the weather in Delhi right now? 
* Give me the latest sports news.
* Convert 100 USD to INR. 
* Who is the CEO of OpenAI?
* Tell me a motivational quote.










