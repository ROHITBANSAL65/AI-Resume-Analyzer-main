# AI Resume Analyzer

An AI-powered Resume Analysis platform that automates resume parsing, candidate profiling, ATS-style evaluation, skill extraction, and personalized career recommendations using Natural Language Processing (NLP), Machine Learning, and Streamlit.

---

## Business Problem

Recruiters often spend significant time manually reviewing resumes, while candidates struggle to understand how well their resumes align with industry expectations and job requirements.

This project automates resume analysis by extracting candidate information, identifying technical skills, evaluating resume quality, predicting candidate profiles, and generating personalized recommendations to improve hiring efficiency and candidate readiness.

---

## Objectives

- Automate resume parsing using Natural Language Processing.
- Extract candidate information and technical skills.
- Evaluate resumes using ATS-inspired scoring.
- Predict candidate experience level.
- Generate personalized career recommendations.
- Provide recruiter analytics through an interactive dashboard.

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| Streamlit | Web Application |
| spaCy | Natural Language Processing |
| PyResparser | Resume Parsing |
| Scikit-learn | Machine Learning |
| Pandas | Data Processing |
| MySQL | Database Management |
| Plotly | Data Visualization |

---

# Project Workflow

## 1. Resume Upload

Candidates upload resumes in PDF format through the Streamlit web application.

---

## 2. Resume Parsing

Resume information is automatically extracted using NLP techniques.

Extracted information includes:

- Name
- Email Address
- Phone Number
- Skills
- Education
- Work Experience
- Certifications

---

## 3. Resume Analysis

The application evaluates resumes by performing:

- Resume Scoring
- Skill Extraction
- Experience Prediction
- Domain Classification
- ATS-style Resume Evaluation

---

## 4. Recommendation Engine

Based on extracted skills and candidate profile, personalized recommendations are generated for:

- Web Development
- Android Development
- iOS Development
- Data Science
- Machine Learning
- UI/UX

The system also recommends additional skills and technologies to improve employability.

---

## 5. Recruiter Dashboard

The recruiter module provides:

- Resume Database
- Candidate Analytics
- Skill Distribution
- Experience Analysis
- Resume Score Comparison

---

# Key Features

- Automated Resume Parsing
- NLP-based Skill Extraction
- ATS-inspired Resume Scoring
- Candidate Experience Prediction
- Domain Classification
- Personalized Skill Recommendations
- Resume Analytics Dashboard
- Recruiter Dashboard
- MySQL Database Integration
- Interactive Streamlit Interface

---

# System Architecture

```text
Resume Upload
      │
      ▼
NLP Resume Parsing
      │
      ▼
Information Extraction
      │
      ▼
Skill Identification
      │
      ▼
Resume Scoring
      │
      ▼
Experience Prediction
      │
      ▼
Recommendation Engine
      │
      ▼
Recruiter Analytics Dashboard
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/ROHITBANSAL65/AI-Resume-Analyzer.git

cd AI-Resume-Analyzer
```

---

## Create Virtual Environment

```bash
python -m venv venv

venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt

python -m spacy download en_core_web_sm
```

---

## Configure Database

Create a MySQL database named:

```text
cv
```

Update the database credentials in `App.py`.

---

## Run the Application

```bash
streamlit run App.py
```

---

# Repository Structure

```text
AI-Resume-Analyzer/
│
├── App/
├── Uploaded_Resumes/
├── pyresparser/
├── screenshots/
├── requirements.txt
└── README.md
```

---

# Skills Demonstrated

- Natural Language Processing (NLP)
- Resume Parsing
- Information Extraction
- Machine Learning
- Recommendation Systems
- Data Processing
- Feature Engineering
- Streamlit Development
- MySQL Database Integration
- Data Visualization
- Python

---

# Future Enhancements

- Multi-language Resume Support
- AI-powered Resume Improvement Suggestions
- Resume Similarity Search
- Interview Question Recommendation
- Cloud Deployment
- LLM-powered Resume Review

---

## Author

**Rohit Bansal**

- **GitHub:** https://github.com/ROHITBANSAL65
- **LinkedIn:** https://www.linkedin.com/in/rohit-bansal-1b2457286
