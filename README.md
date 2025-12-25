\# 🩺 Physician Notetaker:



An AI-based medical NLP system for extracting structured medical information, sentiment analysis, and SOAP note generation from physician–patient conversations.



---



\## 📌 Features:



\- Medical Named Entity Recognition (Symptoms, Diagnosis, Treatment, Prognosis)

\- Structured medical summary generation (JSON)

\- Patient sentiment and intent analysis

\- Automated SOAP note generation

\- Transformer-based NLP models



---



\## 🛠️ Tech Stack:

\- Python

\- spaCy

\- HuggingFace Transformers

\- BERT / DistilBERT

\- Jupyter Notebook



---



\## 📂 Project Structure:



physician-notetaker/

├── physician\_notetaker.ipynb

├── medical\_summary.json

├── sentiment\_intent.json

└── soap\_note.json





---



\## 🚀 Setup Instructions:



\### 1. Create Conda Environment

```bash

conda create -n physician-notetaker python=3.10

conda activate physician-notetaker





2\. Install Dependencies:



pip install spacy transformers torch scikit-learn pandas nltk jupyter

python -m spacy download en\_core\_web\_sm



3\. Run Notebook:



jupyter notebook



• Open physician\_notetaker.ipynb

