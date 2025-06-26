# 🚀 Resume Matcher Web Application

This is a simple yet effective web application that calculates how well a resume matches a given job description based on **semantic similarity** using pre-trained sentence embeddings.

---

## 📌 Overview

This project simulates a basic version of an **Applicant Tracking System (ATS)**. It helps users (especially job seekers) evaluate how closely their resume aligns with a job description, offering a quick and insightful way to optimize resumes before applying.

---

## 🛠️ Tech Stack

- **Python 3.12**
- **Flask** – Lightweight web application framework
- **PyMuPDF (fitz)** – For extracting text from PDF resumes
- **Sentence Transformers** – `all-MiniLM-L6-v2` model for generating semantic embeddings
- **Scikit-learn** – For computing cosine similarity
- **Poetry** – For dependency and environment management

---

## ⚙️ Workflow

1. Upload a **PDF resume**
2. Enter the **job description**
3. The app:
   - Extracts text from the uploaded resume
   - Converts both texts into sentence embeddings
   - Calculates the **cosine similarity** between the two vectors
   - Returns a **match score (%)**

---

## 🎯 Purpose

With the rise of automation in recruitment, it’s essential for candidates to ensure their resumes are aligned with job expectations. This tool offers:
- A fast way to pre-check resume relevance
- Insight into basic semantic similarity concepts
- A hands-on introduction to integrating machine learning models into web apps

---

## 🖼️ User Interface

A minimal UI is built using HTML, CSS, and JavaScript. Features include:
- File upload interface
- Job description input box
- Real-time score display
- Form reset functionality

---

## 🧩 Applications

This project has multiple real-world applications, including:

- ✅ **Job Seekers**: Self-assess how well their resume fits a specific job posting before applying.
- ✅ **Career Coaches & Counselors**: Help clients tailor their resumes for better targeting and relevance.
- ✅ **Recruiters**: Perform quick alignment checks between resumes and open roles.
- ✅ **ATS Simulation for Learning**: Understand how AI-driven systems evaluate content similarity in hiring workflows.
- ✅ **Portfolio Demonstration**: Showcase full-stack AI integration skills for resumes or technical interviews.


## 🚀 Getting Started

### Prerequisites

- Python 3.12+
- Poetry (for dependency management)

### Installation

```bash
git clone https://github.com/your-username/resume-matcher.git
cd resume-matcher
poetry install

###Running the App
'''bash
poetry run python app.py


Then open your browser and visit:
http://127.0.0.1:5000

