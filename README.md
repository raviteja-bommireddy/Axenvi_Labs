# 🗣️ Indian Multilingual Voice-to-English Text Converter
This project provides a robust pipeline that converts spoken language (voice input) from most Indian languages into text, and then translates that text into English. It helps bridge language barriers across India's diverse linguistic landscape by supporting multilingual speech recognition and translation.

## 🚀 Features
🎤 Speech-to-Text (STT): Converts voice input in regional Indian languages (like Hindi, Tamil, Telugu, Kannada, etc.) to native language text.

🌐 Translation: Automatically translates the transcribed native text into English.

📦 Supports a wide range of Indian languages with high accuracy.

⚙️ Modular architecture — easily extendable to new languages or models.

## 📌 Use Case
Ideal for:

Multilingual customer support

Voice command systems

Transcription services

Language learning tools

Accessibility applications

## 🛠️ Tech Stack
Speech Recognition: Google Speech-to-Text API / Whisper by OpenAI / Vosk

Translation API: Google Translate API / IndicTrans / MarianMT

Languages Supported: Hindi, Tamil, Telugu, Kannada, Malayalam, Bengali, Marathi, Gujarati, Punjabi, and more.

## 🧑‍💻 How It Works
User speaks in any Indian language.

The system converts speech to text in the same language.

The native text is then translated into English.

Final output: English translation of the spoken sentence.

[Voice Input: "नमस्ते, आप कैसे हैं?"] 
    ↓ 
[Transcription: "नमस्ते, आप कैसे हैं?"] 
    ↓ 
[Translation: "Hello, how are you?"]

## 📂 Project Structure

project-root/
│
├── models/                 # Pretrained models or APIs used
├── scripts/                # Code for STT and Translation
│   ├── speech_to_text.py
│   └── translate_to_english.py
├── samples/                # Sample audio files
├── requirements.txt        # Python dependencies
└── README.md               # This file

## 🔧 Installation
`Clone the repository`:

git clone https://github.com/yourusername/indian-voice-translator.git
cd indian-voice-translator

`Install dependencies`:

pip install -r requirements.txt
(Optional) Set up API keys if using Google Cloud or other APIs.

## ▶️ Usage
Run the pipeline using a sample audio file:

python main.py --audio samples/hindi_greeting.wav

Expected output:

[Detected Language]: Hindi
[Transcription]: नमस्ते, आप कैसे हैं?
[Translation]: Hello, how are you?
## 🧪 Demo
You can upload an audio sample in your language and see the real-time transcription and translation.

## 🤝 Contributors
[Goutham R]
[Raviteja B]

## 📄 License
This project is licensed under the MIT License.