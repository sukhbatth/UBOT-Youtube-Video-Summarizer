# UBOT: YouTube Video Summarizer and AI Chat 🤖📺

UBOT is an AI-powered web application that allows users to **summarize YouTube videos** and **ask questions** about their content. Built using **Flask**, **Transformer models**, **LangChain**, and **RAG architecture**, UBOT extracts meaningful content from videos using NLP and presents it in an easy-to-understand format.

---

## ✨ Features

- 🔍 **YouTube Video Summarization** using models like **DistilBERT** and **wav2vec2**
- 💬 **Chat Interface** for asking context-based questions about the video
- 🧠 Uses **Retrieval-Augmented Generation (RAG)** and **LangChain** for high-accuracy responses
- 🎙️ Speech-to-text transcription from video audio
- 🌐 Simple and intuitive web UI using Flask + HTML/CSS

---

## 🛠️ Tech Stack

| Component       | Tech Used                          |
|----------------|------------------------------------|
| Frontend       | HTML, CSS, JavaScript              |
| Backend        | Python, Flask                      |
| NLP Models     | DistilBERT, wav2vec2 (via HuggingFace) |
| RAG & Logic    | LangChain, Transformers            |
| Audio Handling | SpeechRecognition, ffmpeg          |

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.8+
- `ffmpeg` installed and added to system path
- API key (if using external video APIs)

### 📦 Installation

```bash
git clone https://github.com/yourusername/ubot-ai-summarizer.git
cd ubot-ai-summarizer
pip install -r requirements.txt
