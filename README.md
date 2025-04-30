## Kinyarwanda Voice Assistant
A simple voice assistant that listens, understands, and responds in Kinyarwanda. This project simulates how humanoid robots can interact with local communities using voice technologies tailored to native languages.

## Overview
This assistant simulates a robot’s:

Ears using ASR (Automatic Speech Recognition),

Brain using simple NLP (Natural Language Processing),

Mouth using TTS (Text to Speech).

It allows users to speak in Kinyarwanda, understands common questions, and responds with synthesized Kinyarwanda speech.

## Objectives
Build a Kinyarwanda-speaking voice assistant.

Convert audio speech to text using KinyaWhisper or SpeechBrain.

Match transcribed text with pre-defined Kinyarwanda Q&A pairs.

Use gTTS or Coqui TTS to generate spoken responses.

Provide a simple UI using Streamlit or Gradio.

## Tools & Technologies
Python 3

KinyaWhisper / SpeechBrain (Speech Recognition)

gTTS / Coqui TTS (Text-to-Speech)


GitHub for version control

## Project Structure
graphql


kinyarwanda-voice-assistant/
│
├── audio/                   # Raw Kinyarwanda speech recordings
├── transcriptions/          # Text outputs from ASR
├── outputs/                 # TTS-generated spoken answers
├── app.py                   # Main script to run the app
├── qa_data.py               # Dictionary with Kinyarwanda Q&A pairs
├── requirements.txt         # List of dependencies
├── interface.py             # Gradio/Streamlit interface
└── README.md                # Project documentation

## Sample Q&A Dictionary (NLP Matching)
python
qa = {
    "U Rwanda rufite intara zingahe?": "Rufite intara eshanu.",
    "Indirimbo y’igihugu y’u Rwanda ni iyihe?": "Ni Rwanda Nziza."
}
## How to Run the Project
1. Clone the Repository

git clone https://github.com/your-username/kinyarwanda-voice-assistant.git
cd kinyarwanda-voice-assistant
2. Install Dependencies
pip install -r requirements.txt
3. Run the App
python main.py

📎 Included Assets
✅ 5 Kinyarwanda audio files (audio/)

✅ Transcribed texts (src/transcribe/)

✅ Spoken TTS responses (outputs/)

✅ Predefined NLP Q&A logic (qa_data.py)