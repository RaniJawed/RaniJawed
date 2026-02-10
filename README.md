# 🤖 AI-Powered Full-Stack Portfolio

A **professional, secure, low-token, AI-enhanced full-stack portfolio** built with modern tools and an AI agent.
This project is designed to be **production-ready**, **YouTube-friendly**, and **easy to understand** for learners.

---

## 🚀 Tech Stack

### ✅ Must Have

* **Next.js + TypeScript** — Frontend
* **FastAPI** — Backend
* **OpenAI Agent SDK** — Agent framework
* **Gemini 2.5 Flash (Free API)** — AI model

### 🟡 Optional (Future-ready)

* SQLite / JSON — Data storage
* Email API — Contact form
* Vercel — Frontend deployment
* Docker — Backend deployment

---

## 🧠 Project Architecture

```
User
 ↓
Next.js (Frontend)
 ↓
FastAPI (Backend)
 ↓
AI Agent (OpenAI Agent SDK)
 ↓
Gemini 2.5 Flash (Free)
```

* **Frontend** handles UI/UX only
* **Backend** manages data, contact form, and AI agent
* **Agent** generates portfolio content and assists users
* **API keys are stored securely in environment variables**

---

## 🔒 Security Note (Important)

* API keys are **never** included in prompts, code, or frontend
* Secrets are stored in **environment variables (.env / Docker / Hosting dashboard)**
* This makes the project **safe for GitHub & public sharing**

---

## 📐 `/sp.constustion`

Defines the **architecture and structure** of the portfolio.

```text
/ sp.constustion
project_name: "AI-Powered Full-Stack Portfolio"

objective:
    Build a professional, fast, secure, and AI-enhanced developer portfolio.
    Keep generation lightweight and production-ready.
    Enable full automation with minimal manual commands.

owner:
    name: Rani Jawed
    role: Full Stack Developer & AI Engineer
    profile_image: "profile.jpg"
    logo: "logo.svg"

frontend:
    framework: Next.js
    language: TypeScript
    styling: Tailwind CSS
    design:
        style: minimal, modern, professional
        responsiveness: true
        animations: subtle only
        accessibility: WCAG 2.1 AA
        seo: enabled

backend:
    framework: FastAPI
    responsibilities:
        - Serve portfolio data
        - Handle contact form
        - Integrate AI agent
    storage: JSON (upgradeable to SQLite)
    security:
        api_keys: from environment variables only

agent:
    sdk: OpenAI Agent SDK
    model: Gemini 2.5 Flash
    purpose: content generation, task execution, assistant
    reasoning: light
    memory: short-term only
    token_policy: minimal
    security:
        secrets_from_env: true
        no_keys_in_prompts: true

sections:
    - Hero
    - About
    - Skills
    - Projects
    - Contact
    - Footer

ui_rules:
    text: concise, professional, readable
    emojis: minimal
    icons: allowed
    images: optimized

deployment:
    frontend: Vercel
    backend: Docker

```

---

## 🧩 `/sp.specify`

Controls **content quality, behavior, and token usage**.

```text
/ sp.specify
global_guidelines:
    tone: professional and friendly
    language: simple English
    verbosity: low
    token_usage: minimal
    avoid_fluff: true

section_rules:

    Hero:
        - Show name, role, short tagline
        - Display profile image
        - One emoji max
        - Include one call-to-action button

    About:
        - Maximum 4 lines
        - Focus on expertise, skills, and goals
        - No storytelling or filler

    Skills:
        - Grouped into Frontend, Backend, Tools
        - Use icons or short lists
        - Keep concise

    Projects:
        - Exactly 3 projects
        - Each project:
            • title
            • one-line description
            • tech stack
            • link

    Contact:
        - Simple form
        - Display email and LinkedIn
        - Short friendly closing line

    Footer:
        - Minimal layout
        - Copyright text only

agent_behavior:
    - Be concise, accurate, and professional
    - Never exaggerate skills or features
    - Generate clean, readable output
    - Do not request or mention API keys
    - Follow Constitution + Section Rules strictly

```

---

## ▶️ How It Works

1. Agent reads `/sp.constustion`
2. Agent follows `/sp.specify`
3. `/sp.implement` generates frontend + backend code
4. Portfolio runs with **low tokens, high performance**

---

# 🎥 YouTube Video Script (Short & Clear)

### 🎬 Intro

"In this video, we are building a **professional AI-powered full-stack portfolio** using modern tools and a free AI model."

---

### 🧠 What We’re Building

"This is not a simple website. It includes:

* Next.js frontend
* FastAPI backend
* An AI agent using OpenAI Agent SDK
* Gemini 2.5 Flash — a free and fast AI model"

---

### 🧱 Architecture Explanation

"The frontend talks to FastAPI, FastAPI talks to the AI agent, and the agent uses Gemini — all securely. API keys are stored in environment variables, not in code."

---

### 🤖 Why AI Agent?

"The agent helps generate portfolio content like About, Skills, and Projects, using very few tokens and clean prompts."

---

### 🔐 Security Best Practice

"We never expose API keys in frontend or prompts. Everything is secure and production-ready."

---

### 🚀 Final Result

"At the end, we get a fast, professional, AI-powered portfolio that we can deploy, share on GitHub, and show to recruiters."

---

### ✅ Outro

"If you like this project, don’t forget to like, subscribe, and check the GitHub repository."

---

## ⭐ Author

**Rani Jawed**
Full Stack Developer & AI Engineer
"# Rani-Jawed-Portfolio" 
