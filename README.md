# Jarvis Assistant

**A chatbot that can hold a conversation with you and translate it into speech!**

[![Language](https://img.shields.io/badge/Language-Python-blue)](https://www.python.org) [![Library](https://img.shields.io/badge/Library-pyttsx3-orange)](https://pypi.org/project/pyttsx3/) [![Library](https://img.shields.io/badge/Library-speech__recognition-orange)](https://pypi.org/project/speech_recognition/) [![Library](https://img.shields.io/badge/Library-openai-orange)](https://pypi.org/project/openai/) [![Library](https://img.shields.io/badge/Library-pyaudio-orange)](https://pypi.org/project/PyAudio/)


## Introduction

This project creates a chatbot that can hold a conversation with you using the OpenAI API and translate it into speech using pyttsx3. The chatbot can also listen to your voice input and convert it into text using speech_recognition.

## Installation

To run this code, you need to install the following libraries:

- openai
- pyaudio
- pyttsx3
- speech_recognition

You can install these libraries using the following command:

```bash
pip install -r requirement.txt
```
## Editing the API Key

To use your own API key for the OpenAI API, follow these steps:

1. Obtain an API key from [OpenAI](https://openai.com).
2. Open the `api_key.py` file in a text editor.
3. Replace the string `API_KEY` with your own API key, keeping the quotation marks.
4. Save the file and close the text editor.

Your code should now use your own API key when making requests to the OpenAI API.


## Usage

To run this code, open a terminal and run the following command:

```bash
python gpt3Bot.py
```
Follow the instructions given by the chatbot to hold a conversation with it.


## Acknowledgements

- [OpenAI API](https://openai.com) for providing the chatbot functionality
- [pyaudio](https://pypi.org/project/PyAudio/) for providing audio recording and playback functionality
- [pyttsx3](https://pypi.org/project/pyttsx3/) for providing text-to-speech functionality
- [speech_recognition](https://pypi.org/project/SpeechRecognition/) for providing speech-to-text functionality

Thank you to the following for their contributions to this project


