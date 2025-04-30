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

* `audio/`                   
* `transcribe/`         
* `outputs/`                 
* `src/`            
* `requirements.txt/`        
* `README.md/`           

## Sample Q&A Dictionary (NLP Matching)
python
{   "muraho": "Muraho neza!",
    "urakora iki?":"Ndi umukozi wa mudasobwa.",
    "Intara zo mu Rwanda ni zingahe?":"Intara 4: Intara y'Amajyaruguru, Intara y'Amajyepfo, Intara  y'Iburengerazuba, Intara y'Iburasirazuba.",
    "Ukunda u Rwanda?":"Yego, ndakunda u Rwanda cyane."
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