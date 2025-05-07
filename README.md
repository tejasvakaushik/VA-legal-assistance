# 🗣️ Legal Assistance Voice App

This is a Python-based voice-controlled application that provides legal assistance information, including shelters, lawyers, and courts. It also supports basic translation functionality.

## 📌 Features

- 🎙️ **Speech Recognition**: Converts spoken commands to text using your microphone.
- 🌐 **Translation**: Translates phrases to another language (default: Hindi) using Google Translate.
- 📚 **Legal Service Directory**: Returns nearby shelters, lawyers, or courts based on voice commands.

## 🚀 How It Works

1. The app listens for voice input.
2. If the user says:
   - `"translate"`: The app will ask for another phrase and translate it to Hindi.
   - `"shelter"`, `"lawyer"`, or `"court"`: It will return relevant service listings.
3. If the command is unrecognized, it prompts the user to try again.

## 🧱 Tech Stack

- **Python**
- [`speech_recognition`](https://pypi.org/project/SpeechRecognition/) – for converting speech to text
- [`googletrans`](https://pypi.org/project/googletrans/) – for translating text

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/legal-assistance-app.git
   cd legal-assistance-app
