# 🚀 SkillGap AI – Career Intelligence Platform

## 📌 Overview

SkillGap AI is an AI-powered Career Intelligence Platform that helps job seekers identify skill gaps between their resume and a target job description. The platform analyzes uploaded resumes and job descriptions, calculates job readiness, identifies missing skills, and generates a personalized learning roadmap to become job-ready faster.

The system leverages Natural Language Processing (NLP), TF-IDF similarity scoring, and domain classification to provide actionable career insights.

---

## ✨ Features

### 📄 Resume & Job Description Analysis

* Upload Resume (PDF)
* Upload Job Description (PDF)
* Automatic text extraction and processing

### 🤖 AI-Powered Skill Gap Analysis

* Resume vs JD comparison
* Missing skill identification
* Matched skill detection
* Job readiness score generation

### 🎯 Domain Classification

Supports multiple technology domains:

* Frontend Development
* Backend Development
* Full Stack Development
* AI / Machine Learning
* Data Science
* DevOps
* Cloud Computing
* Cybersecurity
* Mobile Development
* QA / Testing
* Data Engineering
* Blockchain

### 📚 Personalized Learning Roadmap

* Week-by-week learning plan
* Skill acquisition timeline
* Estimated learning duration
* Resource recommendations

### 🎓 Course Recommendations

For every missing skill:

* YouTube tutorials
* Certification recommendations
* Learning time estimation

### 📊 Interactive Dashboard

* Skill Match Score
* Missing Skills Analysis
* Readiness Curve
* Learning Timeline
* Analytics Charts

### 📧 Email Report Generation

* Personalized HTML reports
* Gmail SMTP integration
* One-click email delivery

### 🌙 Modern UI/UX

* Responsive Design
* Dark/Light Mode
* Animated Components
* Interactive Charts
* Mobile-Friendly Interface

---

## 🏗️ System Architecture

Frontend (React + Vite)
⬇
FastAPI Backend
⬇
PDF Processing (pdfplumber)
⬇
NLP Engine (spaCy + TF-IDF)
⬇
Skill Matching & Domain Detection
⬇
Learning Path Generator
⬇
Dashboard & Email Reports

---

## 🛠️ Tech Stack

### Frontend

* React 18
* Vite
* Tailwind CSS
* Framer Motion
* Recharts
* Axios
* Lucide React

### Backend

* FastAPI
* Python 3.10+
* spaCy NLP
* TF-IDF
* pdfplumber
* Uvicorn
* HTTPX
* Python Dotenv

### Database

* MongoDB

### Deployment

* Vercel (Frontend)
* Render (Backend)

### External Services

* Gmail SMTP
* Adzuna Jobs API

---

## 📂 Project Structure

```text
SkillGapAI/
│
├── backend/
│   ├── main.py
│   ├── analyser.py
│   ├── skill_extractor.py
│   ├── resume_parser.py
│   ├── learning_time_service.py
│   ├── youtube_service.py
│   ├── cert_service.py
│   ├── requirements.txt
│   └── all_skills.json
│
├── frontend/
│   └── vite-project/
│       ├── src/
│       │   ├── components/
│       │   ├── pages/
│       │   ├── hooks/
│       │   └── data/
│       └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/SkillGapAI.git
cd SkillGapAI
```

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend will run at:

```text
http://127.0.0.1:8000
```

---

### Frontend Setup

```bash
cd frontend/vite-project

npm install

npm run dev
```

Frontend will run at:

```text
http://localhost:5173
```

---

## 🔐 Environment Variables

Create a `.env` file inside the backend folder:

```env
SMTP_EMAIL=your_email@gmail.com
SMTP_PASSWORD=your_gmail_app_password
SMTP_NAME=SkillGap AI

ADZUNA_APP_ID=your_adzuna_app_id
ADZUNA_APP_KEY=your_adzuna_app_key

FRONTEND_URL=http://localhost:5173
```

---

## 📊 Key Functionalities

### Skill Gap Detection

Compares candidate skills against job requirements and highlights missing competencies.

### Job Readiness Scoring

Calculates how prepared a candidate is for a specific role.

### Learning Path Generation

Creates a structured roadmap to close skill gaps efficiently.

### Course Recommendation Engine

Suggests learning resources based on missing skills.

### Domain Classification

Automatically identifies the most relevant technology domain.

---

## 🚀 Deployment

### Frontend (Vercel)

```bash
npm run build
```

Deploy using:

* Vercel
* Netlify

### Backend (Render)

```bash
uvicorn main:app --host 0.0.0.0 --port $PORT
```

Deploy as a Python Web Service on Render.

---

## 🔮 Future Enhancements

* JWT Authentication
* Resume Builder
* Interview Question Generator
* Multi-JD Comparison
* LinkedIn Integration
* Mobile Application
* AI Chat Assistant
* LLM-Based Skill Analysis

---

## 📈 Project Highlights

* AI-Powered Resume Analysis
* NLP-Based Skill Extraction
* Personalized Learning Roadmap
* Real-Time Job Readiness Scoring
* Interactive Analytics Dashboard
* Modern SaaS-Style UI
* Responsive Design
* Email Report Generation

---

## 👨‍💻 Author

**Prasoon Pathak**

MCA Candidate | Full Stack Developer | AI Enthusiast

GitHub: https://github.com/prasoonpathak967

LinkedIn: Add Your LinkedIn Profile Here

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, don't forget to give it a star on GitHub!
