
![Logo](https://github.com/kounsaiswaroop/Jarvis-VoiceAssistant/blob/main/jarvis-banner.jpg)


# Jarvis – Voice Activated Virtual Assistant

Jarvis is an AI-powered, voice-activated virtual assistant capable of performing everyday tasks such as browsing the web, playing music, fetching news, and answering queries using OpenAI's GPT-3.5-turbo model. It aims to function similarly to Google Assistant or Alexa, activated by the wake word “Jarvis”.






## 🛠️ Core Features

- 🎙️ Voice Recognition
- 🗣️ Text-to-Speech (TTS)
- 🌐 Web Browsing
- 🎵 Music Playback
- 📰 News Fetching
- 🧠 GPT Integration (OpenAI)


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## 🔁 Workflow Overview

- Initialization
- Greets the user: "Initializing Jarvis...".
- Wake Word Detection
- Listens for "Jarvis" using voice recognition.
- Responds with: "Ya".
- Command Processing
- Classifies and executes the command:
- Open websites
- Play music
- bRead news
- Answer questions using GPT-3.5-turbo
- Response Delivery
- Replies using either pyttsx3 or gTTS depending on the settings or availability.




## 📚 Libraries and Modules Used

| Library              | Purpose                                |
| -------------------- | -------------------------------------- |
| `speech_recognition` | Voice input & command recognition      |
| `pyttsx3`            | Offline text-to-speech                 |
| `gTTS + pygame`      | Online text-to-speech + audio playback |
| `webbrowser`         | Launch websites                        |
| `openai`             | Communicate with GPT-3.5-turbo         |
| `requests`           | API calls for news, etc.               |
| `os`                 | File system access                     |
| `musicLibrary`       | Custom module for music management     |



## Support

For support, email saiswaroopghadai@gmail.com or follow on X.

