# 📝 AI Text Summarizer using T5 Transformer

A modern AI-powered Text Summarizer built with **FastAPI**, **Hugging Face Transformers**, and **PyTorch**. This application generates concise summaries from long text using a fine-tuned T5 model.

---

## 🚀 Features

- 🤖 AI-powered text summarization
- ⚡ FastAPI backend
- 🎨 Beautiful and responsive web interface
- 🧠 T5 Transformer model
- 💻 GPU (CUDA) and CPU support
- 📋 One-click summary generation

---

## 🛠️ Tech Stack

- Python 3.11+
- FastAPI
- Hugging Face Transformers
- PyTorch
- HTML
- CSS
- JavaScript
- Jinja2

---

## 📂 Project Structure

```
TEXTSUMMARIZER_APP/
│
├── app.py
├── index.html
├── README.md
├── requirements.txt
├── .gitignore
└── saved_summary_model/
```

---

## 📦 Installation

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/TEXTSUMMARIZER_APP.git

cd TEXTSUMMARIZER_APP
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python -m uvicorn app:app --reload
```

Open:

```
http://127.0.0.1:8000
```

---

## 📷 Demo

Home Page

```
Paste your text
        ↓
Click Summarize
        ↓
AI Generated Summary
```

---

## ⚠️ Model Files

The trained model is **not included** because GitHub limits files larger than **100 MB**.

Place your trained model inside:

```
saved_summary_model/
```

Example:

```
saved_summary_model/
├── config.json
├── generation_config.json
├── model.safetensors
├── tokenizer.json
└── tokenizer_config.json
```

---

## 📌 Future Improvements

- PDF Summarization
- DOCX Summarization
- Upload Text Files
- Dark Mode
- Copy Summary Button
- Download Summary
- Multiple Language Support

---

## 👨‍💻 Author

**Sagar Roy**

GitHub:
https://github.com/sagar-roy-676

---

## ⭐ Support

If you like this project, don't forget to **Star ⭐ the repository**.

```

---

## Also create a `requirements.txt`

Create a file named **requirements.txt** and add:

```text
fastapi
uvicorn
torch
transformers
jinja2
sentencepiece
accelerate
pydantic
safetensors
```

This will make your project look much more professional and easier for others to run.

Your repository will then include:

```
TEXTSUMMARIZER_APP/
│── app.py
│── index.html
│── README.md
│── requirements.txt
│── .gitignore
└── saved_summary_model/   (excluded from GitHub)
```

This is a solid structure for an AI/ML project that you can showcase on your resume and GitHub profile.
