# 🚀 AI Text Summarizer (FastAPI + Transformers)

An end-to-end **AI-powered Text Summarization Web App** built using FastAPI and Hugging Face Transformers.

This application takes long text input and generates a concise summary using a fine-tuned T5 model.

---

## ✨ Features

- 🧠 Transformer-based text summarization  
- ⚡ FastAPI backend for high performance  
- 🌙 Clean and responsive UI with Dark Mode  
- 📄 Handles long text (up to 512 tokens)  
- 🔍 Beam search for better summary generation  

---

## 🛠️ Tech Stack

- **Backend:** FastAPI  
- **Model:** T5 (Hugging Face Transformers)  
- **Deep Learning:** PyTorch  
- **Frontend:** HTML, CSS, JavaScript  
- **Templating:** Jinja2  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Harshit-pundir/Ai-text-summarizer-fastapi.git
cd Ai-text-summarizer-fastapi
```

### 2️⃣ Create virtual environment
```bash
python -m venv venv
```

### Activate

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

---

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

---

### 4️⃣ Model Setup ⚠️

Model files are not included due to size.

Place your trained model inside:
```
saved_summary_model/
```

---

### 5️⃣ Run the app
```bash
uvicorn app:app --reload
```

---

### 6️⃣ Open in browser
```
http://127.0.0.1:8000
```

---

## 📡 API Endpoint

### POST `/summarize/`

**Request**
```json
{
  "dialogue": "Your long text here..."
}
```

**Response**
```json
{
  "summary": "Generated summary..."
}
```

---

## 🧠 How it Works

1. Clean input text  
2. Add "summarize:" prefix  
3. Tokenize input  
4. Generate summary using model  
5. Decode output  

---

## 📌 Learning Outcomes

- Built an end-to-end ML system  
- Learned transformer-based text generation  
- Implemented FastAPI backend  
- Understood preprocessing pipeline  

---

## 🚧 Future Improvements

- Deploy on cloud  
- Add ROUGE score  
- File upload support  
- Multi-language support  

---

## ⚠️ Notes

- Model not included (size issue)  
- Use CPU PyTorch if no GPU  

---

## 🤝 Contributing

Feel free to fork and improve!

---

## 📬 Contact

Connect with me on LinkedIn 🚀
https://www.linkedin.com/in/harshit-pundir-a5b112332/
