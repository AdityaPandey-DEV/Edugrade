# EduGrade

**AI-powered grading and feedback system built with Google Gemini — Google Developer Challenge submission.**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-8E75B2?style=flat-square&logo=google&logoColor=white)

---

## What It Does

Streamlines the assignment workflow by using Google Gemini AI to evaluate student submissions and provide detailed, personalized feedback based on custom rubrics.

**Key Features:**
- **Automated Grading** — Gemini evaluates submissions against rubrics
- **Personalized Feedback** — AI-generated suggestions for improvement
- **Teacher Dashboard** — manage assignments, rubrics, and grades
- **Student Dashboard** — submit work and view AI feedback instantly

## Architecture

```
Student/Teacher Dashboards (React) ↔ Express.js API ↔ MongoDB (Data)
                                              ↕
                                       Google Gemini API (Grading Engine)
```

## Tech Stack

| Component | Technology |
|---|---|
| Frontend | React, CSS |
| Backend | Node.js, Express.js |
| AI | Google Gemini API |
| Database | MongoDB |

## My Role

I designed the grading pipeline, planned the role-based dashboard, and structured the Gemini prompt engineering for rubric-aligned grading. Code generation was accelerated using AI tools; Gemini API prompt tuning and integration are mine.

## Quick Start

```bash
git clone https://github.com/AdityaPandey-DEV/Edugrade.git && cd Edugrade
npm install
# Configure .env (MongoDB + Gemini API Key)
npm start
```

---

<div align="center">

*Architected & built by [Aditya Pandey](https://github.com/AdityaPandey-DEV) — AI-augmented development*

</div>
