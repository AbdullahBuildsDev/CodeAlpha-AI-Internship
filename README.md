<div align="center">

# 🚀 CodeAlpha — Artificial Intelligence Internship

### Hands-on AI projects built during the CodeAlpha AI Internship

[![Internship](https://img.shields.io/badge/CodeAlpha-AI%20Internship-4361ee?style=for-the-badge)](https://www.codealpha.tech)
[![Python](https://img.shields.io/badge/Python-3.x-3776ab?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**By [Abdullah Awan](https://github.com/AbdullahBuildsDev)** · AI Intern @ CodeAlpha

</div>

---

## 📖 About This Internship

This repository contains the projects I built during my **Artificial Intelligence
Internship at [CodeAlpha](https://www.codealpha.tech)** — a software development
company that provides students with real-world, hands-on experience in emerging
technologies.

The internship required completing a minimum of **2–3 tasks** from the AI domain.
I went further and built **four complete, production-style projects**, each with a
clean architecture and a polished, modern web interface. Every project runs
**100% locally and free** — no paid APIs, no cloud services.

> 📄 My official internship offer letter is included in [`docs/`](docs/).

---

## 🗂️ Projects

| # | Project | What it does | Core AI |
|---|---------|--------------|---------|
| 🎥 | **[Object Detection & Tracking](CodeAlpha_ObjectDetectionTracking/)** | Detects, tracks & counts objects in images, video, and **live webcam** | YOLOv8 + ByteTrack |
| 🧠 | **[Smart FAQ Chatbot](CodeAlpha_FAQChatbot/)** | A **semantic** chatbot that understands meaning, not just keywords (RAG-style) | sentence-transformers |
| 🎵 | **[AI Music Generation](CodeAlpha_MusicGeneration/)** | Composes **brand-new melodies** with a deep-learning model, playable & downloadable | PyTorch LSTM |
| 🌐 | **[Language Translation Tool](CodeAlpha_LanguageTranslationTool/)** | Translates text between languages with a clean desktop UI | Google / MyMemory |

Each folder has its own detailed `README.md`, `requirements.txt`, and runnable app.

---

### 🎥 1 · Object Detection & Tracking
Real-time computer vision with **YOLOv8**. Detects 80 object classes, assigns each
object a persistent **tracking ID** (ByteTrack), and **counts unique objects**.
Three modes — image, video, and live webcam — in a smooth web dashboard.

`YOLOv8` · `ByteTrack` · `OpenCV` · `Gradio` · `PyTorch`

### 🧠 2 · Smart Semantic Chatbot
A retrieval chatbot that embeds a knowledge base with a local
**sentence-transformers** model and answers questions by **semantic similarity** —
so it understands *meaning*, not just matching words. Includes an automatic
pure-Python **TF-IDF fallback** so it always works.

`sentence-transformers` · `RAG` · `cosine similarity` · `NLTK` · `Gradio`

### 🎵 3 · AI Music Generation
A **PyTorch LSTM** neural network trained on tonal note sequences that composes
original melodies. Choose a key, length, and creativity; listen in-browser and
download the MIDI. Audio is synthesized locally — no sound fonts needed.

`PyTorch` · `LSTM` · `pretty_midi` · `Gradio`

### 🌐 4 · Language Translation Tool
A clean desktop (Tkinter) translator with auto-detect, copy, and text-to-speech.
Uses a primary + **automatic backup translation engine** for reliability.

`deep-translator` · `Tkinter`

---

## 🛠️ Tech Stack

**Languages & Core:** Python 3
**AI / ML:** PyTorch · YOLOv8 (Ultralytics) · sentence-transformers · LSTM
**Computer Vision:** OpenCV · ByteTrack
**NLP:** sentence-transformers · NLTK · TF-IDF
**Audio:** pretty_midi
**UI/UX:** Gradio (custom-themed) · Tkinter

---

## 🚀 Getting Started

Each project is self-contained. In general:

```bash
# clone the repo
git clone https://github.com/AbdullahBuildsDev/CodeAlpha-AI-Internship.git
cd CodeAlpha-AI-Internship

# pick a project
cd CodeAlpha_ObjectDetectionTracking

# set up and run
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

See each project's own `README.md` for details.

---

## 📁 Repository Structure

```
CodeAlpha-AI-Internship/
├── CodeAlpha_ObjectDetectionTracking/   # 🎥 YOLOv8 detection + tracking
├── CodeAlpha_FAQChatbot/                # 🧠 Semantic chatbot
├── CodeAlpha_MusicGeneration/           # 🎵 LSTM music generator
├── CodeAlpha_LanguageTranslationTool/   # 🌐 Translation tool
├── docs/                                # 📄 Internship offer letter
├── LICENSE
└── README.md
```

---

## 🙋‍♂️ About Me

**Abdullah Awan** — AI Intern @ CodeAlpha
Building practical AI projects in computer vision, NLP, and deep learning.

- 🔗 GitHub: [@AbdullahBuildsDev](https://github.com/AbdullahBuildsDev)

---

<div align="center">

### ⭐ Built with dedication during the CodeAlpha AI Internship

*If you find these projects helpful, consider giving the repo a star!*

</div>
