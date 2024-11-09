# Speech-to-Text-Transcription

## Overview

This project provides a complete end-to-end workflow within a Jupyter Notebook, allowing users to transcribe Hindi audio files into text, translate the text into English, and perform sentiment analysis on the translated text. It is designed with simplicity and ease of experimentation in mind.

## Features

- **Hindi Speech-to-Text**: Transcribes Hindi audio files (e.g., call center conversations) into text.
- **Translation to English**: Translates the Hindi transcription to English.
- **Sentiment Analysis**: Analyzes the sentiment of the English translation, determining if it's positive, negative, or neutral.
- **Single-Notebook Workflow**: All processing steps are contained in a single Jupyter Notebook, enabling easy sequential execution and modification.

## Project Structure

```plaintext
├── data/                     # Folder for Hindi audio files
├── models/                   # Pre-trained models for ASR and NLP (optional)
├── hindi_speech_pipeline.ipynb # Main Jupyter Notebook for the entire pipeline
├── config.yaml               # Configuration file for model and audio settings
├── requirements.txt          # Python package dependencies
└── README.md                 # Project documentation
