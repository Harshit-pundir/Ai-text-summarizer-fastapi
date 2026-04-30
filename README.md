🚀 AI Text Summarizer (FastAPI + Transformers)

An end-to-end AI-powered Text Summarization Web App built using FastAPI and Hugging Face Transformers.

This application takes long text input and generates a concise summary using a fine-tuned T5 model.

✨ Features
🧠 Transformer-based text summarization
⚡ FastAPI backend for high performance
🌙 Clean and responsive UI with Dark Mode
📄 Handles long text (up to 512 tokens)
🔍 Beam search for better summary generation
🛠️ Tech Stack
Backend: FastAPI
Model: T5 (Hugging Face Transformers)
Deep Learning: PyTorch
Frontend: HTML, CSS, JavaScript
Templating: Jinja2

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/ai-text-summarizer-fastapi.git
cd ai-text-summarizer-fastapi
2️⃣ Create virtual environment
python -m venv venv

Activate:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Model Setup ⚠️

Model files are not included due to size.

Place your trained model inside:

saved_summary_model/
5️⃣ Run the app
uvicorn app:app --reload
6️⃣ Open in browser
http://127.0.0.1:8000
📡 API Endpoint
POST /summarize/

Request

{
  "dialogue": "Your long text here..."
}

Response

{
  "summary": "Generated summary..."
}
🧠 How it Works
Clean input text
Add "summarize:" prefix
Tokenize input
Generate summary using model
Decode output
📌 Learning Outcomes
Built an end-to-end ML system
Learned transformer-based text generation
Implemented FastAPI backend
Understood preprocessing pipeline
🚧 Future Improvements
Deploy on cloud
Add ROUGE score
File upload support
Multi-language support
⚠️ Notes
Model not included (size issue)
Use CPU PyTorch if no GPU
🤝 Contributing

Feel free to fork and improve!

📬 Contact

Connect with me on LinkedIn 🚀
