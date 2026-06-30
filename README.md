# 🚀 Deployment Intelligence Assistant

An AI-powered DevOps toolkit that helps engineering teams respond to incidents faster — built with HTML, JavaScript, and Groq's Llama 3 AI.

**🔗 Live Demo: [Click here to open the app](https://youverma356-ai.github.io/deployment-intelligence-assistant)**

---

## What problem does this solve?

When a deployment breaks in production, engineers waste hours doing the same things manually:
- Reading through hundreds of log lines to find the error
- Writing incident reports from scratch under pressure
- Figuring out what caused the problem
- Deciding how to safely roll back
- Writing post-mortem reports after the incident

This app uses AI to compress all of that from hours to seconds.

---

## The 7 AI-powered modules

| Module | What it does |
|---|---|
| 📋 Log Analyzer | Paste deployment logs → AI finds errors, warnings, and root issues |
| 🚨 Incident Report Reader | Paste an incident report → AI extracts gaps and missing information |
| 🏗️ Architecture Review | Describe your system → AI finds single points of failure and risks |
| 🔍 Root Cause Finder | Describe symptoms → AI gives ranked probable causes with how to verify each |
| ✅ Deploy Checklist | Describe your change → AI generates pre/during/post deployment checklist |
| ↩️ Rollback Plan | Describe your deployment → AI creates step-by-step emergency rollback plan |
| 📄 Post-Mortem Generator | Paste rough notes → AI produces a blameless post-mortem report |

---

## UX features

- ⏳ Loading spinner while the AI generates a response, so you always know it's working
- 📋 One-click copy button on every AI output
- ⬇️ Export any AI output (logs, checklists, post-mortems, etc.) directly as a PDF

---

## How to use it

1. Open the [live app](https://youverma356-ai.github.io/deployment-intelligence-assistant)
2. Get a free API key from [Groq Console](https://console.groq.com) (no credit card needed)
3. Paste your API key in the yellow bar at the top
4. Click any tab → click "load example" to see it work instantly

---

## Tech stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript (no framework) |
| AI Model | Llama 3.3 70B via Groq API |
| PDF Export | jsPDF |
| Deployment | GitHub Pages (free) |

---

## Why I built this

I wanted to demonstrate two things at once:
1. Deep understanding of real DevOps and SRE workflows — log analysis, incident management, rollback planning, and post-mortems are things engineering teams deal with every day
2. Practical AI integration skills — knowing how to write effective prompts, call an LLM API, and turn raw AI output into something useful

---

## What I learned building this

- How to integrate an LLM API (Groq) into a frontend app
- How to write structured prompts that produce consistent, useful output
- How DevOps teams handle incidents — the full lifecycle from detection to post-mortem
- How to deploy a web app using GitHub Pages
- How to design good loading and feedback states (spinners, copy confirmations) for AI-powered tools

---

## Future improvements

- [ ] Add file upload support for logs (drag and drop)
- [ ] Connect to real logging tools like Datadog or Splunk
- [ ] Add user authentication for team use
- [ ] Save and search past analyses

---

*Built by Ajeet | B.Tech IIT (BHU) Varanasi*
