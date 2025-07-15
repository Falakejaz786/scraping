# 📚 Automated Book Publication Workflow
> *AI-powered, agentic, RL-enhanced, human-in-the-loop content pipeline*

---

## 🚀 Overview

This project is an **end-to-end, agentic AI workflow** designed to automate the publication pipeline of book chapters. It demonstrates:

✅ Web scraping & screenshots  
✅ AI rewriting and reviewing (LLM-powered)  
✅ RL-style reward optimization  
✅ Human-in-the-loop editing  
✅ Versioning with semantic search  
✅ Voice output generation

---

## 🎯 Objective

> Create a system that fetches content from a web URL, applies AI-driven rewriting ("spin"), allows multiple human-in-the-loop iterations, and ensures consistent, version-controlled, searchable results with voice support.

**Key capabilities:**
- ✅ Scraping & screenshots with RL-based rewards
- ✅ AI Writer & Reviewer loops
- ✅ Human editing stage
- ✅ Version storage and semantic search
- ✅ Text-to-speech audio generation

---

## 🛠️ Tech Stack

| Tool / Library        | Purpose                                   |
|------------------------|-------------------------------------------|
| **Python (Colab)**     | Development and orchestration            |
| **Playwright**         | Automated, full-page website screenshots |
| **BeautifulSoup**      | Web scraping and text extraction         |
| **Groq API (LLM)**     | AI Writer & Reviewer                     |
| **ChromaDB**           | Versioning and semantic search           |
| **SentenceTransformers** | Embeddings for search                  |
| **gTTS**               | Voice synthesis for narration            |

---

## 📦 Features

### 📸 1. Scraping & Screenshots
- Fetches full-page screenshots of any URL
- Scrapes clean text from HTML
- RL-style reward system scoring text length and paragraph structure

---

### ✍️ 2. AI Writing & Review
- AI Writer “spins” chapters into modern, polished style
- AI Reviewer improves grammar, readability, and clarity
- Reinforcement Learning loop for multiple iterations with rewards

---

### 🧑‍💻 3. Human-in-the-Loop
- Human editor can review and modify AI-reviewed text
- Multiple iteration support ensures collaborative refinement

---

### 🗂️ 4. Versioning & Semantic Search
- Saves original, AI-written, reviewed, and human-edited versions
- Embedding-powered semantic search using SentenceTransformers + ChromaDB

---

### 🔊 5. Voice Support
- Converts final text into audio narration
- Uses gTTS for simple, multilingual TTS generation

---

## 📋 Notebook Flow

✔️ Install dependencies  
✔️ Import libraries  
✔️ Input Groq API Key  
✔️ Screenshot + display  
✔️ Scrape text + reward score  
✔️ AI Writer → Reviewer → Human Editor loop with RL rewards  
✔️ Version storage in ChromaDB  
✔️ Semantic search over versions  
✔️ Text-to-speech audio playback

---

## 🧪 Example URLs

Use these to test scraping and screenshot features:

```

[https://en.wikisource.org/wiki/The\_Gates\_of\_Morning/Book\_1/Chapter\_1](https://en.wikisource.org/wiki/The_Gates_of_Morning/Book_1/Chapter_1)

```

---

## 🔎 Example Semantic Search Queries

```

summary of chapter one
village daily life
description of the lagoon and coral reef

```

---

## 🗺️ How to Use in Google Colab

1️⃣ Clone or download this repo  
2️⃣ Open the `.ipynb` notebook in **Google Colab**  
3️⃣ Install dependencies (first cell)  
4️⃣ Enter your **Groq API Key** when prompted  
5️⃣ Follow step-by-step cells:
   - Screenshot
   - Scraping + RL reward
   - AI Writer & Reviewer
   - Human editing
   - Version storage + semantic search
   - TTS voice generation  
6️⃣ Download and upload your completed notebook back to GitHub

---
