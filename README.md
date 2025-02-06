# 🌍🎙️ **LangBridge-AI-Powered-Translation-Hub** 🍝🔊 
🚀 **Effortless Batch Translation & Speech Processing with AI**  

## 🌟 **Overview**  

🎮 **AI-Powered Language Translator** is an intelligent text and speech translation system that leverages **Google Translate API**, **Speech Recognition**, and **Text-to-Speech (TTS)** to provide seamless translations across multiple languages. Whether you're translating bulk text from a file 📂 or converting speech 🎤 into multilingual text, this project has you covered!  

---

## ✨ **Key Features**  

👉 **Batch Translation** – Translate bulk text from a `.txt` or `.csv` file into multiple languages at once.  
👉 **Multilingual Support** – Supports translation into languages like Telugu (`te`), Hindi (`hi`), Kannada (`kn`), and more.  
👉 **Speech Recognition 🎤** – Convert spoken words into translatable text.  
👉 **Text-to-Speech 🔊** – Convert translated text into speech using `gTTS`.  
👉 **File Support 📂** – Read input from `.txt` and `.csv` files and save translated content as structured output.  
👉 **Interactive UI 🎮** – Powered by **Thinker**, enabling a user-friendly experience.  

---

## 🏠 **Tech Stack**  

📑 **Programming Language**: Python 🐍  
💻 **Libraries Used**:  
- `googletrans` 🌍 – Google Translate API for multilingual support  
- `gtts` 🎤 – Google Text-to-Speech  
- `speech_recognition` 🎮 – Convert voice input into text  
- `pandas` 📊 – Handle structured data  
- `thinker` 🎮 – Build an interactive UI  

---

## 📂 **How to Use?**  

### 💎 **Batch Translation from a File**  
1️⃣ Create a `.txt` or `.csv` file with English sentences.  
2️⃣ Run the `batch_translate()` function to translate text into multiple languages.  
3️⃣ The translations are saved in `translations.csv` for easy access.  

Example Usage:  
```python
from translator import batch_translate

batch_translate("sentences.txt")
```

---

## 🎤 **Speech-to-Text Translation**  

1️⃣ Speak into the microphone 🎤  
2️⃣ Convert speech to text using **SpeechRecognition**  
3️⃣ Translate the recognized text into the target language  
4️⃣ Optionally, generate an audio output using **gTTS**  

Example Usage:  
```python
from translator import speech_to_text

translated_text = speech_to_text("en", "te")  # Translate English speech to Telugu
print(translated_text)
```

