# 🗣️ Voice Assistant in Python

A simple voice-activated assistant built with Python. It can respond to your voice commands to perform actions like telling the time, opening websites, or playing music.

## 🚀 Features

- Listens for voice commands using your microphone
- Converts speech to text and responds with spoken feedback
- Performs actions like:
  - Telling the current time
  - Opening Google or YouTube
  - Playing music from a local folder
  - Exiting on command

## 🛠️ Technologies Used

- [`speech_recognition`](https://pypi.org/project/SpeechRecognition/)
- [`pyttsx3`](https://pypi.org/project/pyttsx3/)
- `webbrowser`, `datetime`, `os` (standard Python libraries)

## 🔧 How to Run

1. **Install dependencies**
   ```bash
   pip install SpeechRecognition pyttsx3 pyaudio
