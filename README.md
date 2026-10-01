# 🎯 AI Resume-to-Interview Coach

A no-code AI chatbot that reads a candidate's resume, benchmarks it 
against a target role, and runs a live mock interview with real-time 
feedback — built end-to-end on Zapier's chatbot platform.

**🔗 Live Demo:** [ai-resume-to-interview-bot.zapier.app](https://ai-resume-to-interview-bot.zapier.app)
**📄 Full Case Study PDF:** [Download here](AI-Resume-to-Interview-Coach-Portfolio-Case-Study.pdf)
---

## 📋 Overview

| | |
|---|---|
| **Role** | AI Chatbot Developer, No-Code Automation & Prompt Design |
| **Platform** | Zapier Chatbots (No-Code AI) |
| **Tags** | Zapier Chatbots · LLM Prompt Engineering · Conversation Design · No-Code Automation |

## 🎯 The Problem

Most job seekers rehearse the same recycled questions off a blog post, 
regardless of their actual background or the role they're chasing. 
Prep that isn't tied to the resume in front of a hiring manager doesn't 
build real confidence.

## 💡 The Solution

I designed a conversational AI agent that ingests a candidate's actual 
resume and target role, scores the fit, then runs a tailored mock 
interview — mixing technical and behavioral questions with structured, 
STAR-based feedback after every answer.

## 🛠️ How It Works

**Step 1 — Greeting**
Warm, on-brand greeting prompts the user to share a resume or target 
job title — no blank-page confusion.

**Step 2 — Intake**
Natural free-text input. The bot doesn't require a rigid form — it 
parses intent from plain conversation.

**Step 3 — Personalize**
Before generating anything, it confirms the role — so every question 
that follows is relevant, not generic.

## 🔍 Behind the Build

**Why This Matters**
This is the actual logic layer I wrote — not a default template. It's 
the difference between "I connected an AI tool" and "I designed how 
the AI thinks."

**Design Decisions**
Chose a 7-step guided flow over an open-ended chatbot so the AI never 
loses the thread — every reply moves the candidate one step closer to 
interview-ready.

**Coaching Method**
Feedback is scaffolded on the STAR framework, a structure familiar to 
interview coaches — so the AI's advice reads like a real coach, not a 
generic chatbot.

## 🎓 Tools & Skills

`Zapier Chatbots` `LLM System Prompting` `Conversation Flow Design` 
`No-Code Automation` `User Intake Design` `AI Product Thinking` 
`Career Coaching Domain Knowledge` `Iterative Testing`

## 📝 System Logic (directive.txt)

The actual conversation flow I authored for the bot's behavior:
# OBJECTIVE
Act as an AI Resume-to-Interview Coach. Guide the user through 
resume feedback and a tailored mock interview.

CONVERSATION FLOW
01 Collect the resume (PDF or image), if not already shared.
02 Ask for the target job title or job description.
03 Score resume-to-role fit: matched strengths, missing 
   keywords, one improvement.
04 Offer a mock interview built around that role.
05 Ask 3–5 tailored questions, mixing technical and behavioral.
06 Give short, structured feedback after every answer (STAR 
   method).
07 Close with a strengths/gaps summary and offer another round.

# STYLE — friendly, encouraging, structured with headers & bullets
