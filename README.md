# 📝AI Resume Analyzer
**AI Resume Analyzer** is an intelligent web application that evaluates how well a candidate’s resume matches a specific job description using advanced Natural Language Processing (NLP) techniques and Large Language Models (LLMs).

---
## 🚀 Features

- ✅ **ATS-style Similarity Score** using BERT embeddings
- 🤖 **LLM-based Evaluation Report** analyzing skills, experience, and alignment
- 📈 **Score Breakdown** with detailed explanations (✅ Matched, ❌ Unmatched, ⚠️ Unclear)
- 🔍 **Keyword Match Analysis** – shows what's present or missing in your resume
- 📄 **Downloadable Report (PDF)** with full AI-generated feedback

---

## 🧠 How It Works

1. Upload your **Resume (PDF)**
2. Enter the **Job Description**
3. The app:
   - Extracts and compares the content using **BERT embeddings**
   - Uses **Groq’s LLaMA 3.3-70B** model to generate a detailed evaluation
   - Extracts and highlights **important keywords**
4. Provides:
   - A similarity score (like ATS)
   - An LLM-generated report with improvement suggestions
   - A downloadable PDF of the report

---
## 💡 Tech Stack
- **Python**
- **Streamlit** – Frontend interface
- **pdfminer.six** – PDF text extraction
- **sentence-transformers** – BERT embeddings for similarity
- **scikit-learn** – Cosine similarity
- **Groq API** – Access to LLaMA 3.3-70B model for analysis
- **ReportLab** – Generate downloadable PDF report
- **dotenv** – Secure API key handling

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nandinee-Sharma/AI_Resume_Analyzer
   cd resume-analyzer
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
3. **Create a .env file**
   GROQ_API_KEY=your_groq_api_key_here
4. **Run the app**
   streamlit run app.py
