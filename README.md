# 🧠 Resume AI Toolkit

![Domain](https://img.shields.io/badge/Domain-Career_&_Job_Search-0d6efd?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-AI_Skills_Toolkit-6f42c1?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Claude_AI-7c3aed?style=for-the-badge)
![Skills](https://img.shields.io/badge/Skills-4-059669?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-198754?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Ready_to_Use-f39c12?style=for-the-badge)

## Turn Claude into Your Personal Resume & Interview Coach

A complete set of **4 specialized Claude skills** that systematically fix the two places most resumes die — the ATS and the 6-second human scan — then let you practice the interview that follows.

---

# 🚀 Project Highlights

- 🧠 **4 production-ready Claude skills** for end-to-end resume & interview preparation
- 📊 **ATS Resume Diagnostician** — full parse-risk score, critical killers, prioritized fixes
- 🔑 **Keyword Gap Analyzer** — precise missing-keyword analysis against any job description
- ✍️ **Bullet Impact Rewriter** — turns weak bullets into quantified achievement statements
- 🎤 **Hiring Manager Interviewer** — realistic interview simulation with probing + scored feedback
- 📑 Includes one-page cheat sheet and MIT license
- ⚡ Drop any `SKILL.md` into a Claude Project and start immediately

---

# 📌 Results at a Glance

| Metric | Value |
|--------|------:|
| 🧠 Specialized Skills | **4** |
| 🎯 Core Problems Solved | **ATS rejection + weak bullets + missing keywords + interview anxiety** |
| 🛠 Primary Platform | **Claude AI (Projects / Custom Instructions)** |
| 📄 Deliverables | Skills + Cheat Sheet + Full Documentation |
| 📜 License | **MIT** |
| 🎯 Objective | Land more interviews with stronger resumes |

---

# 🎯 Project Snapshot

| Attribute | Details |
|-----------|---------|
| **Role** | AI Product / Career Tools Builder |
| **Project Type** | AI Skills Toolkit |
| **Platform** | Claude AI |
| **Skills** | 4 specialized instruction packages |
| **Target Users** | Job seekers, career switchers, students, professionals |
| **Deliverables** | 4 SKILL.md files, README, Cheat Sheet, LICENSE |

---

# 📖 Table of Contents

- [Why This Exists](#-why-this-exists)
- [The 4 Skills](#-the-4-skills)
- [Recommended Workflow](#-recommended-workflow)
- [Quick Start](#-quick-start)
- [Repository Structure](#-repository-structure)
- [Skill Deep Dive](#-skill-deep-dive)
- [Example Prompts](#-example-prompts)
- [Pro Tips](#-pro-tips)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Improvements](#-future-improvements)
- [About This Project](#-about-this-project)
- [Connect With Me](#-connect-with-me)

---

# 📋 Why This Exists

Most resumes never get read by a human. They die in two places:

1. **The ATS** — silently rejected because of formatting, missing keywords, or poor structure
2. **The 6-second human scan** — a recruiter or hiring manager glances and moves on

Even strong candidates often fail because:
- Their resume has ATS-breaking layout issues
- Critical job-specific keywords are missing
- Bullets describe responsibilities instead of measurable impact
- They walk into interviews unprepared for realistic probing

This toolkit gives Claude four specialized "brains" so you can systematically fix both problems and then practice the interview that follows.

---

# 🧠 The 4 Skills

| # | Skill | What it does | Best used when |
|---|-------|--------------|----------------|
| **01** | [ATS Resume Diagnostician](01-ats-resume-diagnostician/SKILL.md) | Full ATS + structural audit with risk score and prioritized fixes | You have a resume and want to know why it's getting rejected |
| **02** | [Keyword Gap Analyzer](02-keyword-gap-analyzer/SKILL.md) | Precise gap analysis between your resume and a target job description | You have both a resume and a job description |
| **03** | [Bullet Impact Rewriter](03-bullet-impact-rewriter/SKILL.md) | Turns weak/responsibility bullets into quantified achievement statements | Your bullets feel bland or lack numbers |
| **04** | [Hiring Manager Interviewer](04-hiring-manager-interviewer/SKILL.md) | Realistic hiring-manager interview simulation with probing + feedback | You want to practice before real interviews |

---

# 🔄 Recommended Workflow

```text
1. Diagnose   →  Skill 01 on your current resume
        │
        ▼
2. Target     →  Skill 02 with resume + job description
        │
        ▼
3. Strengthen →  Skill 03 on weak bullets
        │
        ▼
4. Practice   →  Skill 04 for that same role
```

---

# ⚡ Quick Start

### Claude Projects (Recommended)

1. Create a new **Claude Project**
2. Open **Project Instructions**
3. Paste the entire content of the desired `SKILL.md`
4. Upload your resume (and job description for Skills 02 & 04) as Project knowledge
5. Start chatting — Claude follows the skill process automatically

### Alternatives

- Paste the skill body into a **Custom Style** or system prompt
- Paste the skill at the top of a new chat (one-shot)

---

# 📁 Repository Structure

```text
resume-ai-toolkit/
│
├── 📄 README.md
├── 📄 LICENSE
├── 📄 CONTRIBUTING.md
├── 📄 .gitignore
│
├── 📂 01-ats-resume-diagnostician/
│   └── 📄 SKILL.md
│
├── 📂 02-keyword-gap-analyzer/
│   └── 📄 SKILL.md
│
├── 📂 03-bullet-impact-rewriter/
│   └── 📄 SKILL.md
│
├── 📂 04-hiring-manager-interviewer/
│   └── 📄 SKILL.md
│
└── 📂 docs/
    └── 📄 cheat-sheet.pdf          (optional one-pager)
```

---

# 🔍 Skill Deep Dive

## 01 — ATS Resume Diagnostician

Performs a ruthless, evidence-based diagnosis of your resume.

**Outputs:**
- Overall **ATS Parse Risk Score** (0–100)
- Critical ATS killers (tables, columns, graphics, non-standard dates, etc.)
- Structural & formatting issues
- Content red flags
- Role-specific gaps (when a target role is provided)
- Prioritized fix list + quick wins you can do in <15 minutes

---

## 02 — Keyword Gap Analyzer

Reverse-engineers job descriptions the way modern ATS systems score them.

**Outputs:**
- Must-have vs nice-to-have keyword extraction
- Gap analysis table (keyword, priority, present?, frequency, insertion location)
- Ranked list of critical missing keywords
- Natural, authentic insertion recommendations
- Keyword density & authenticity warnings

> Never invents experience — only recommends keywords that can be truthfully supported.

---

## 03 — Bullet Impact Rewriter

Transforms weak, responsibility-focused bullets into high-impact achievement statements.

**For every bullet you get:**
1. **Conservative** — safe, corporate-friendly
2. **Strong** (Recommended) — balanced impact
3. **Bold** — high-energy, startup/FAANG style

Plus diagnosis of what's weak and metric opportunities (never invents numbers).

---

## 04 — Hiring Manager Interviewer

Runs a realistic interview simulation that stays in character as a hiring manager.

**Features:**
- Adopts tone based on company type (startup / Big Tech / enterprise)
- Asks one question at a time and probes for depth
- Mixes behavioral, situational, and resume deep-dives
- Structured feedback + score after answers
- Full debrief with overall score, strengths, and areas to improve

Session controls: `next question` · `feedback` · `make it harder` · `switch to technical` · `end interview and debrief`

---

# 💬 Example Prompts

**After loading Skill 01:**
> Here's my resume. Target role: Senior Product Manager at a Series B SaaS company. Diagnose it.

**After loading Skill 02:**
> Here's my resume and the job description. Show me the keyword gaps and where to insert the missing ones.

**After loading Skill 03:**
> Rewrite these bullets. I have approximate metrics for a few of them.

**After loading Skill 04:**
> I'm interviewing for a Staff Engineer role at a Big Tech company. Let's do a full behavioral + technical simulation. Start when ready.

---

# 💡 Pro Tips

- Always provide **full resume text** — screenshots kill accuracy
- For Skill 02, paste the **complete job description**
- Skills are deliberately rigorous — they will not flatter weak content
- You can switch skills inside the same Claude Project by updating the Project Instructions
- In Skill 04 you can say `make it harder`, `switch to technical`, or `end interview and debrief` at any time

---

# 🛠 Skills Demonstrated

This project demonstrates a combination of product thinking, prompt engineering, and career-domain expertise.

### 💻 Technical & AI Skills

![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-7c3aed?style=flat-square)
![Claude Skills](https://img.shields.io/badge/Claude_Skills-0d6efd?style=flat-square)
![System Design](https://img.shields.io/badge/Skill_System_Design-198754?style=flat-square)
![Documentation](https://img.shields.io/badge/Technical_Writing-6c757d?style=flat-square)

- Prompt engineering & skill architecture
- Structured output design
- Claude Projects / Custom Instructions
- Modular instruction packages
- Clear documentation & onboarding

### 📊 Domain Skills

![ATS](https://img.shields.io/badge/ATS_Optimization-dc3545?style=flat-square)
![Resume Writing](https://img.shields.io/badge/Resume_Writing-fd7e14?style=flat-square)
![Interview Prep](https://img.shields.io/badge/Interview_Prep-20c997?style=flat-square)
![Career Tools](https://img.shields.io/badge/Career_Tools-6f42c1?style=flat-square)

- ATS compatibility analysis
- Keyword strategy for job descriptions
- Achievement-oriented resume writing
- Behavioral & technical interview simulation
- End-to-end job-search workflow design

### 💼 Product & Communication Skills

![Product Thinking](https://img.shields.io/badge/Product_Thinking-0d6efd?style=flat-square)
![UX Writing](https://img.shields.io/badge/UX_Writing-6f42c1?style=flat-square)
![Portfolio](https://img.shields.io/badge/Portfolio_Design-198754?style=flat-square)

- Problem framing & solution design
- User onboarding experience
- Clear, actionable documentation
- Portfolio-ready presentation

---

# 🚀 Future Improvements

Ideas already on the radar:

- 📄 Cover letter generator skill
- 🔗 LinkedIn About + Experience optimizer
- 💰 Offer negotiation practice skill
- 🎯 Role-specific skill packs (Software Engineering, Product, Data, Marketing)
- 📊 Before/after resume score tracking
- 🌐 Multi-language support

Contributions and new skill ideas are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

---

# 🌟 Why This Project Matters

Sending resumes into the void is exhausting. Most candidates don't lack experience — they lack a systematic way to:

1. Make the resume survive machines
2. Make the resume impress humans in 6 seconds
3. Prove they can perform in the interview

This toolkit turns Claude into a rigorous, opinionated coach that forces clarity, metrics, and evidence instead of generic advice.

---

# 📖 About This Project

This project reflects my approach to building useful tools:

> **Identify a real pain point → Design focused solutions → Package them so anyone can use them immediately → Document clearly.**

Beyond the skills themselves, the focus is on creating something practical that job seekers can apply the same day.

---

# 🤝 Connect With Me

Thank you for exploring this project.

If you'd like to discuss AI tools, career systems, data analytics, or potential collaboration, feel free to connect.

### 👤 Kartik Singh (Kith_)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kartik_Singh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartik-singh-54854a216)
[![GitHub](https://img.shields.io/badge/GitHub-Vampsoutside-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vampsoutside)
[![Substack](https://img.shields.io/badge/Substack-Kainsrt-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://substack.com/@kainsrt)

---

# ⭐ Support This Project

If you found this toolkit helpful:

- ⭐ Star this repository
- 🍴 Fork it and adapt the skills for your own workflow
- 💼 Connect with me on LinkedIn
- 📚 Explore my other projects ([IT Service Desk Analytics](https://github.com/Vampsoutside/it-service-desk-analytics))

Your feedback and suggestions are always welcome.

---

<p align="center">
Built for people who are tired of sending resumes into the void<br>
Designed as an AI Skills & Career Tools Portfolio Project
</p>
