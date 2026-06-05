# 🎯 Interview Trainer Agent using IBM watsonx Orchestrate

AI-powered Interview Preparation Assistant built using IBM watsonx Orchestrate, IBM Cloud, RAG (Retrieval-Augmented Generation), and GPT-OSS 120B.

---

## 📌 Problem Statement

**Problem Statement No. 22 – Interview Trainer Agent**

An Interview Trainer Agent powered by RAG helps users prepare for job interviews by generating personalized interview questions, model answers, and preparation strategies based on:

* Job role
* Experience level
* Technical domain
* Resume information

The system retrieves role-specific interview content, HR guidelines, behavioral scenarios, and technical questions from a curated knowledge base.

---

# 🚀 Project Overview

The Interview Trainer Agent is an AI-powered virtual interview coach designed to help students and job seekers improve their interview preparation through:

* Technical interview practice
* HR & behavioral interview simulation
* AI-generated model answers
* Personalized interview guidance
* RAG-powered knowledge retrieval

The solution was developed during the **IBM SkillsBuild Internship on AI & Cloud Technologies** in collaboration with:

* IBM SkillsBuild
* Edunet Foundation
* AICTE

---

# 🧠 Features

✅ Technical Interview Question Generation
✅ HR & Behavioral Interview Preparation
✅ Personalized Interview Guidance
✅ RAG-Based Knowledge Retrieval
✅ AI-Generated Model Answers
✅ STAR Method Coaching
✅ Real-Time AI Chat Assistant
✅ IBM Cloud Deployment
✅ Embedded Web Frontend

---

# 🛠️ Technology Stack

| Technology                | Purpose                           |
| ------------------------- | --------------------------------- |
| IBM Cloud                 | Cloud infrastructure & deployment |
| IBM watsonx Orchestrate   | AI Agent Builder                  |
| GPT-OSS 120B              | Large Language Model              |
| RAG                       | Retrieval-Augmented Generation    |
| IBM Granite / GPT Models  | AI reasoning & generation         |
| HTML5 / CSS3 / JavaScript | Frontend Development              |
| LangFlow                  | Workflow orchestration            |
| FAISS / ChromaDB          | Vector database for RAG           |

---

# 🏗️ System Architecture

```text
User Input
(Job Role + Experience Level)
        ↓
IBM watsonx Orchestrate Agent
        ↓
RAG Knowledge Base Retrieval
        ↓
GPT-OSS 120B / Granite Model
        ↓
Interview Questions + Model Answers + Tips
```

---

# 📚 Knowledge Base (RAG)

The following interview preparation PDFs were used as the RAG knowledge base:

1. 75 Most Important LeetCode DSA Questions
2. AI/ML 100 Interview Questions
3. Common Job Interview Questions & Answers
4. HR Interview Questions & Answers
5. Java Interview Question List
6. Java Technical Interview Questions & Answers
7. Resume Guide 2020
8. Top 100 Common Interview Questions

---

# ⚙️ Agent Workflow

### Step 1 — User Input

User enters:

* Job role
* Experience level
* Interview domain

### Step 2 — Query Processing

IBM watsonx Orchestrate processes the query using configured behavior prompts.

### Step 3 — RAG Retrieval

Relevant interview-related content is retrieved from uploaded PDFs.

### Step 4 — LLM Processing

GPT-OSS 120B / Granite model generates:

* Technical questions
* HR questions
* Model answers
* Improvement tips

### Step 5 — AI Response

Structured interview preparation content is displayed to the user.

---

# 💻 Frontend

A custom responsive web frontend was developed with:

* Hero section
* Embedded AI chatbot
* Modern UI/UX
* Real-time interaction

The IBM watsonx embed script was integrated using:

* `agentId`
* `agentEnvironmentId`
* `wxOConfiguration`

---

# 🌟 Role of Agentic AI

Agentic AI enables the Interview Trainer Agent to function as an intelligent virtual interview coach instead of a basic chatbot.

The system:

* Understands user context
* Retrieves role-specific knowledge
* Generates adaptive interview questions
* Provides personalized feedback
* Simulates real interview scenarios

This makes the platform interactive, context-aware, and goal-driven.

---

# 🔮 Future Scope

* Resume Upload & Parsing
* Voice-Based Mock Interviews
* Confidence Scoring
* ATS Resume Checker
* LinkedIn Job Integration
* PDF Feedback Reports
* Multi-Language Support
* Advanced Multi-Agent Pipelines using LangFlow

---

# 📸 Project Screenshots

## IBM watsonx Orchestrate Dashboard

<img width="442" height="232" alt="image" src="https://github.com/user-attachments/assets/ca04ab32-7a25-4aa1-b6c3-e5832fdcaa6d" />


## Knowledge Base Upload

<img width="442" height="232" alt="image" src="https://github.com/user-attachments/assets/14b43f48-c780-4684-8274-8ee8d7f221cf" />


## Website Frontend

<img width="443" height="232" alt="image" src="https://github.com/user-attachments/assets/89900615-d67c-402e-a23b-82fa1452c9da" />


## AI Interview Response

<img width="442" height="233" alt="image" src="https://github.com/user-attachments/assets/9ad71a7b-f8aa-4054-a940-25e7567c47c8" />

<img width="443" height="233" alt="image" src="https://github.com/user-attachments/assets/98abe60d-f5ef-4d4f-ae63-ac6eac4e0272" />


---

# 🏆 IBM SkillsBuild Certifications

Completed certifications include:

* Getting Started with Artificial Intelligence
* Getting Started with Cybersecurity
* Journey to Cloud
* Large Language Model Basics
* Mastering the Art of Prompting

---

# 📂 Repository Structure

```text
├── README.md
├── app.json
├── InterviewTrainer_Presentation.pptx
├── InterviewTrainer_InternshipReport.docx
├── screenshots/
├── frontend/
└── assets/
```

---

# 👨‍💻 Author

### K Chinmay Krishna

B.Tech – Computer Science & Engineering
GITAM University, Hyderabad

IBM SkillsBuild Internship Project
AI & Cloud Technologies – 2026

---

# 📜 License

This project was developed for educational and internship purposes under the IBM SkillsBuild Internship Program.
