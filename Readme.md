# 14566 AI Stress & Trauma Assessment System

## Overview

The **14566 AI Stress & Trauma Assessment System** is an AI-assisted triage platform designed for the **National Helpline Against Atrocities (NHAA) – 14566**. It helps identify potential distress and vulnerability in victims or complainants during their initial interaction with the helpline.

The system analyzes **voice interactions, speech patterns, pauses, emotional indicators, and textual narratives** using Artificial Intelligence and Natural Language Processing.

## Key Features

* 🎙️ **Voice-based complaint recording**
* 📝 **AI-powered speech transcription**
* 🤖 **Emotion and distress analysis**
* 📊 **Stress Vulnerability Index (SVI)**
* 🚦 **Risk classification: Low, Moderate, High, Critical**
* 🆔 **Automatic case ID generation**
* 👨‍💼 **Operator dashboard**
* 🌐 **Language detection and confidence**
* 🔄 **Real-time AI-assisted case assessment**

## System Workflow

```text
Victim / Complainant
        ↓
Voice / Text Input
        ↓
React Frontend
        ↓
FastAPI Backend
        ↓
Speech & NLP Analysis
        ↓
Gemini AI
        ↓
SVI Calculation
        ↓
Risk Classification
        ↓
Operator Dashboard
        ↓
Human Review & Action
```

## Stress Vulnerability Index

The SVI provides a score between **0–100** based on multiple indicators such as distress, fear, anxiety, urgency, vulnerability, and contextual signals.

| Score  | Risk Level |
| ------ | ---------- |
| 0–24   | Low        |
| 25–49  | Moderate   |
| 50–74  | High       |
| 75–100 | Critical   |

The SVI is intended as a **decision-support mechanism**, not a psychological or medical diagnosis.

## Technology Stack

**Frontend:** React.js, JavaScript, Vite, HTML/CSS, MediaRecorder API
**Backend:** Python, FastAPI, Uvicorn
**AI:** Google Gemini API, NLP, Speech & Emotion Analysis
**Development:** Git, GitHub, VS Code, npm

## USP

The system introduces an **AI-powered first-contact vulnerability assessment layer** to help operators identify cases that may require priority attention.

Unlike a conventional complaint-registration system, it combines **voice analysis + NLP + emotion indicators + contextual AI + SVI scoring + human oversight** in one workflow.

## Future Scope

Future versions can support multilingual Indian languages, live-call analysis, historical SVI trends, advanced speech features, secure role-based access, and continuous human-feedback-based improvement.

> **AI assists the operator; the final decision always remains with the authorized human professional.**
