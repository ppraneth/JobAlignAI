# JobAlignAI

**AI-powered Resume and Job Description Matcher using NLP**

JobAlignAI applies advanced natural language processing to compare resumes with job descriptions, evaluating how closely they align and providing a relevance score along with meaningful analytical insights.

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
