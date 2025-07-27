# AI-Powered-Multi-Language-Translator# 🌍 AI-Powered Multi-Language Translator

A real-time, AI-based multilingual translation tool built using Hugging Face Transformers and Gradio. Translate text seamlessly between English and widely spoken global languages using pre-trained MarianMT models.

## 🚀 Features

- 🔁 Supports 12 translation directions:
  - English ⇄ Spanish
  - English ⇄ French
  - English ⇄ German
  - English ⇄ Russian
  - English ⇄ Arabic
  - English ⇄ Chinese
- ⚡ Real-time translation with minimal latency
- 🧠 Uses MarianMT models from Helsinki-NLP (via Hugging Face)
- 💻 Simple and interactive web interface (Gradio)
- 🔌 Modular design – easy to extend with more languages
- 🔐 Runs locally or via temporary web link (no user data stored)

---

## 📦 Technologies Used

- **Python**
- **Hugging Face Transformers** (`MarianMTModel`, `MarianTokenizer`)
- **Gradio** (for the web interface)
- **Pre-trained OPUS-MT models** by Helsinki-NLP

---

## 🛠 How It Works

1. User inputs text and selects a translation direction.
2. The appropriate pre-trained MarianMT model is loaded.
3. Text is tokenized using `MarianTokenizer`.
4. Model generates translated tokens.
5. Output is decoded and displayed in real-time.

---

## ▶️ Getting Started

### 🔧 Requirements

- Python 3.7+
- `transformers`
- `torch`
- `gradio`

### 📥 Installation

```bash
git clone https://github.com/your-username/ai-multilanguage-translator.git
cd ai-multilanguage-translator
pip install -r requirements.txt
