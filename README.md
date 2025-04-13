# 🧠 AI Study Buddy - Your Smart Learning Assistant

AI Study Buddy is an intelligent assistant designed to help students study more effectively. It supports multilingual queries, understands your learning materials, and answers questions in your preferred language.

## 🚀 Features

- 🔍 **Semantic Search** over study documents using embeddings + FAISS
- 💬 **Multilingual support**: English, French, Arabic, Hindi, Spanish
- 🧠 **Powered by Gemini** for intelligent responses
- 🗃️ **Retrieval-Augmented Generation (RAG)** to ground answers in your notes
- 📚 **PDF Understanding** and text chunking
- 🌍 **Language detection and translation** (Google Translate)

## 📁 Dataset

- `ai-revision-guide.pdf` from the Kaggle dataset: `study-buddy-resources`

## 🛠️ Tech Stack

- Python, Gemini Flash 2.0 (via `google.generativeai`)
- FAISS for vector search
- Google Translate API
- Langdetect for language identification


## ⚙️ Setup

1. Install dependencies:
pip install -r requirements.txt

2. Add your `GOOGLE_API_KEY` to your environment or notebook using:
```python
import os
os.environ["GOOGLE_API_KEY"] = "your_api_key_here"

3. Upload your PDF notes and run the notebook!

# Built as part of the Kaggle x Google Generative AI Capstone Project.