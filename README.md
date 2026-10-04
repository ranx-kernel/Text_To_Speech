# 🎙️ Speech-to-Text System

## 📌 Objective

The objective of this project is to convert spoken audio into written text using an automatic speech recognition model.

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- Whisper
- PyTorch
- Librosa
- SoundFile
- Gradio
- Google Colab

## 🧠 Model

This project uses the `openai/whisper-tiny` model for Automatic Speech Recognition.

Whisper converts spoken language from an audio file into text.

## 🔄 Workflow

Audio File
↓
Audio Processing
↓
Whisper Model
↓
Speech Recognition
↓
Transcribed Text
↓
Gradio Interface

## ✨ Features

- Upload audio files
- Convert speech into text
- Supports common audio formats
- Uses a pretrained Whisper model
- Interactive Gradio interface
- Simple Google Colab implementation

## 🧪 Example

### Input

Audio recording:

"Artificial intelligence is transforming the world."

### Output

```text
Artificial intelligence is transforming the world.
