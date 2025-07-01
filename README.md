# JobAlignAI

**AI-powered Resume and Job Description Matcher using NLP.**

JobAlignAI use natural language processing to intelligently match candidate resumes with job descriptions, providing a similarity score and insights based on textual relevance.

---

## 🚀 Features

- ✅ Resume Parsing (supports PDF and DOCX)
- ✅ Job Description Parsing
- ✅ Matching Score Computation using **TF-IDF + Cosine Similarity**
- ✅ User-friendly interface built with **Gradio**

---

## 🧪 How to Run Locally

```bash
# Install dependencies
pip install -r requirements.txt

# Download necessary NLP resources
python -m nltk.downloader all
python -m spacy download en_core_web_sm

# Launch the Gradio frontend
python frontend/app_gradio.py
