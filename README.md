# AI-Research-Paper-Evaluation

##🚀 Overview

This project is an AI-based web application designed to evaluate research papers and improve their publication readiness. The system focuses on two major aspects: plagiarism detection and grammar analysis (Grammarly-like evaluation) to assess originality and writing quality.

The application allows users to upload research papers in PDF or text format and generates structured feedback on content similarity, grammar issues, readability, and overall writing quality.

##🎯 Objectives

-Detect plagiarism using similarity analysis

-Analyze grammar and writing quality

-Provide automated feedback for improvement

-Assist researchers in increasing publication success rate

##🧠 Technologies Used
Programming & Framework

Python

Streamlit

NLP & Machine Learning

NLTK

spaCy

Scikit-learn

TF-IDF Vectorization

Cosine Similarity

Data Processing & Visualization

Pandas

NumPy

Matplotlib

Other Tools

PyPDF2 (PDF text extraction)

LanguageTool / TextBlob (Grammar analysis)

##🔍 Key Features

📑 Upload research papers (PDF or TXT format)

🔎 Plagiarism detection using TF-IDF + Cosine Similarity

✍ Grammar checking and writing suggestions

📊 Data visualization for text analysis

🌐 Interactive web interface built using Streamlit

##🗂 Dataset

Collected and prepared a dataset of approximately 200–250 research papers

Applied text preprocessing including tokenization, stop-word removal, and lemmatization

##⚙️ How It Works

User uploads a research paper

Text is extracted and preprocessed using NLP techniques

TF-IDF vectorization is applied

Cosine similarity is calculated for plagiarism detection

Grammar analysis is performed

System generates structured feedback report

##▶️ How to Run the Project
pip install -r requirements.txt
streamlit run app.py

##👩‍💻 Contribution

This was a 3rd-year major group project. I contributed to:

Dataset preparation

NLP preprocessing

Plagiarism detection implementation

Integration with Streamlit frontend

##📌 Future Improvements

Advanced semantic plagiarism detection

Deep learning-based text evaluation

Automated citation quality analysis

Cloud deployment
