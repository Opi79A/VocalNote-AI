# 🎙️ Voice-to-Text Logger

An efficient Python application that transcribes live speech into text and logs it into a file.

## ✨ Features
* **Real-time Transcription**: Uses `SpeechRecognition` library with Google's API.
* **Smart Noise Reduction**: Adjusts for ambient noise automatically to ensure clarity.
* **UTF-8 Logging**: Saves text to `output.txt` with full character support.
* **Continuous Listening**: Runs in a loop to capture multiple sentences.

## 🛠️ Requirements
To run this project, you need to install the following libraries:
```bash
pip install SpeechRecognition pyttsx3 pyaudio
