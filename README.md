
<img width="1024" height="1536" alt="ChatGPT Image Jan 29, 2026, 08_28_30 PM" src="https://github.com/user-attachments/assets/685209a2-c08c-4097-af15-1d6ba363b451" />

# Security+ Agent Interactive Practice Exam (Prototype)

## Overview
**Security+ Agent** is a prototype study application built to help learners prepare for the **CompTIA Security+** exam by turning a static practice-question experience into an **interactive quiz session**.


Instead of manually reading questions, guessing, and flipping pages to check answers, this app delivers questions one-by-one, grades selections instantly, and provides **clear explanations for both correct and incorrect answers** (using the source’s explanations). At the end, users get a **score summary** to measure readiness.

---
## 🎥 Click Watch Demo ⬇️
[![Video](https://github.com/user-attachments/assets/16120972-37fa-4092-bf0e-dbbd7f524c1e)](https://youtu.be/QVMKE7oFwC0?si=lSgr5oDQJwKxweXu)
---

## The Problem I Solved
Studying from practice PDFs is effective—but the workflow is inefficient:
- You lose momentum constantly switching between questions and answer keys  
- It’s hard to track performance across sessions  
- Explanations are often skipped because they’re inconvenient to access  
- There’s no “test day” feel (timed flow, final score, structured session)

This project solves that by creating a **clean, guided test experience** that’s easy to repeat daily.

---

## What the App Does (High Level)
- Runs a practice exam session using a question bank sourced from Professor Messer material
- Lets the user choose how many questions to attempt (**10 to 90**)
- Presents questions in a simple, interactive flow
- Grades answers immediately
- Shows **why** an answer is correct or incorrect
- Generates an **end-of-session percentage score** to track readiness

---

## Key Features
- **Configurable Practice Sets**: choose session length (10–90 questions)
- **Immediate Feedback**: instant correct/incorrect grading
- **Explanation-Driven Learning**: reinforces understanding, not guessing
- **Progress & Score Summary**: percentage score at completion
- **Study Resources Built-In**: quick links to supporting videos/study guides

---


## Tech Stack (Simple View)
This prototype is built as a lightweight web app:
- **Frontend**: interactive UI for the quiz flow  
- **Backend**: session logic and grading  
- **Content Parsing**: converts a static question source into structured quiz data  

*(Intentionally kept high-level here.)*

---

## Typical User Flow
1. User launches the app  
2. Selects number of questions (10–90)  
3. Answers questions one-by-one  
4. Receives instant feedback + explanation each time  
5. Gets final percentage score and a readiness snapshot  

---



## Notes on Content & Attribution
This is a **personal study prototype** intended to enhance a learner’s workflow.
- Question content and explanations are attributed to their original source (Professor Messer materials).
- This repo is meant to demonstrate application design and workflow automation—not to redistribute protected content.
