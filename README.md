# ResumeMatcher-Machine-Learning-Project-
Python, Flask, scikit-learn, NLP  Created an AI-based system that matches resumes with job  descriptions using TF-IDF, Cosine Similarity, and Euclidean Distance.  Used NLP preprocessing and skill extraction. Evaluated results with a  Confusion Matrix. Integrated a Flask web interface for real-time,  interactive outputs.

# Resume Matcher 

## Overview
This is a Flask web application that matches uploaded resumes to a job description using TF-IDF vectorization and **cosine similarity**. It also extracts a predefined list of skills from the job description and each resume and reports a confusion-matrix style breakdown (True Positives, False Positives, False Negatives) for each resume.

## Features
- Upload multiple resumes (`.pdf`, `.docx`, `.txt`) via a web form.
- Extract text from each resume (PyPDF2, docx2txt).
- Extract skills from both Job Description and Resumes using a predefined SKILL_SET.
- Compute TF-IDF vectors for job + resumes and compute cosine similarity/Euclidean distance.
- Return top matching resumes sorted by highest similarity (%).
- Display extracted skills and confusion-matrix per resume.

## Requirements
- Python 3.8+
- Install dependencies:

File Structure
app_euclidean/
├─ app.py
├─ templates/
│  └─ index.html
├─ uploads/
└─ README.md

