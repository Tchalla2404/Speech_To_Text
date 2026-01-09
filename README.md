# Speech_To_Text
A Python-based Speech-to-Text system that converts spoken audio into written text using speech recognition techniques. The project supports real-time and audio file transcription and showcases practical applications of AI and machine learning in voice-based systems.
This project demonstrates a simple and effective **Speech-to-Text** system using **OpenAI’s Whisper model**. The notebook installs the required dependencies and converts spoken audio into text using a pre-trained speech recognition model.

## Project Overview

The notebook uses the Whisper command-line interface to transcribe an audio file into text. Whisper is a powerful automatic speech recognition (ASR) system capable of producing accurate transcriptions for English speech.

The project is minimal and focused, making it easy to understand how speech-to-text conversion works using modern AI models.

## Features

- Converts audio speech into text
- Uses OpenAI’s Whisper pre-trained model
- Simple command-line based transcription
- Suitable for beginners exploring speech recognition

## Technologies Used

- Python
- OpenAI Whisper
- FFmpeg
- Jupyter Notebook

## Notebook Workflow

1. Install Whisper directly from GitHub
2. Install FFmpeg for audio processing
3. Run Whisper on an audio file using a selected model

## Installation

Run the following commands (already included in the notebook):

```bash
pip install git+https://github.com/openai/whisper.git
sudo apt update && sudo apt install ffmpeg
