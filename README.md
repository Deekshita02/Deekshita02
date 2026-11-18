# Hi, I'm Deekshita 👋

AI/ML Engineer | B.Tech CSE 2025 | CGPA 8.93

I build LLM agents and RAG systems with automated evaluation and human oversight, backed by full-stack engineering (Java, Spring Boot, React.js) so what I build actually ships.

🔭 Open to AI Engineer, GenAI, and AI/ML roles (India + remote/international). Also open to software engineering roles.

🌱 Learning: LangGraph multi-agent workflows, advanced RAG architectures, cloud deployment (AWS/GCP)

📫 Contact: deekshitapilaka@gmail.com

🚀 Featured Projects

Meeting Action-Item Agent — Python · LangGraph · Streamlit · Gemini API · Automated Eval · 🔴 Live Demo

Extracts structured action items (owner, task, deadline, confidence) from meeting transcripts, with schema validation and a hard human-approval gate before persisting data. Rebuilt as a LangGraph workflow (extractor → rule-based grounding check → conditional LLM reviewer with a bounded revision loop) so suspicious extractions get an independent second check before reaching a human. Evaluated against a 12-case harness (ambiguous ownership, missing deadlines, prompt injection, misleading dates, similar names etc.) — 36/36 checks passing, matching the single-agent baseline at ~0.2s added average latency for the extra review step. Full decision log and known limitations documented in the repo.

PDF Q&A RAG Chatbot — LangChain · FAISS · Sentence-Transformers · Gemini API · Streamlit · 🔴 Live Demo

Retrieval-Augmented Generation chatbot built end-to-end across a 93-chunk vector index from a 15-page document — chunking, embeddings, FAISS indexing, and grounded LLM response generation to reduce hallucination. Debugged real integration issues (deprecated imports, API rate limits, empty-index edge cases) and shipped with defensive error handling and secret management.

AI Support Agent for AmazonHelp — Python · Gemini API · Retrieval · TF-IDF/Logistic Regression

Given an incoming customer tweet to @AmazonHelp, classifies intent into one of 8 categories, drafts a reply grounded in retrieval over 4,497 real historical brand-response pairs, and decides auto-handle vs. escalate with a stated reason. Reproducible, leakage-free TF-IDF baseline (59.5% accuracy / 0.394 macro F1 vs. a 45% trivial baseline); LLM-judge evaluation showed 93% agreement with manual scoring on relevance. Documented decision log covers what was deliberately not built (fine-tuning, multi-turn handling, a learned escalation model) and why.

Support Ticket AI System — FastAPI · Streamlit · pandas · Groq API

Natural-language query engine over support ticket data plus rule-based anomaly detection. The LLM (Groq gpt-oss-120b) never computes numbers directly — it translates questions into a validated, structured query spec that's executed deterministically in pandas, guaranteeing numeric accuracy. Anomaly detection (abnormally long resolution times, aging high-priority tickets) is pure rule-based logic, no LLM involved.

Invoice Data Extraction — Tesseract OCR · Random Forest · scikit-learn · Python

Traditional ML only, no LLMs: Tesseract OCR → preprocessing and grouping of text pieces → feature engineering (position, text shape, neighbouring words) → Random Forest classifier labelling each piece → cleaning and validation rules (GSTIN checks, net + tax = total) → structured JSON.

Mental Health EEG Classification (Deep Learning + IoT) — TensorFlow · Keras · CNN · Firefly Optimization

Group research project (team of 5), co-author — 7-class EEG-based mental disorder classification. Worked on preprocessing and the CNN model; Firefly optimization raised held-out test accuracy from 88% to 92% (PSD + functional connectivity features) and from 79% to 86% (PSD only). Co-authored the paper and presented to a review panel.

JobTrack – Full-Stack Job Application Tracker — Java · Spring Boot · JWT · PostgreSQL · React.js · Docker · 🔴 Live Demo

Built a secured REST API (stateless JWT auth, BCrypt hashing, Spring Security, protected CRUD, status filtering) on a relational PostgreSQL schema hosted on Neon, with a React.js frontend deployed on Vercel; containerized with Docker.

🛠️ Tech Stack

AI / ML & GenAI: LangChain, LangGraph, FAISS, Sentence-Transformers, Google Gemini API, Groq API, RAG, Prompt Engineering, Agent Evaluation & Guardrails, PyTorch, TensorFlow, Keras, CNN, Scikit-learn

Languages: Python, Java, JavaScript, SQL

Backend & Web: FastAPI, Spring Boot, Spring Security, REST APIs, JWT, React.js, PostgreSQL, MySQL, Pandas, NumPy

Tools: Git, GitHub, Docker, VS Code, Google Colab, Streamlit Cloud, Vercel

📫 Connect

Reach me at deekshitapilaka@gmail.com — open to AI/ML engineering roles, relocation-ready.

LinkedIn · GitHub
