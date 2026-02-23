# Hi, I'm Bharath R 👋

**Software Engineer** with **4 years of experience** building scalable backend systems and production-ready GenAI applications.

I specialize in **Python · FastAPI · Flask · REST APIs · LLMs · RAG pipelines** — with a focus on solving real-world problems at scale, not just prototyping ideas.

> Currently open to backend / GenAI engineering roles. [Let's connect →](https://linkedin.com/in/YOUR_HANDLE)

---

## 🚀 Featured Projects

### [JanamSaathi AI](https://github.com/Bharath-Ramamurthy/JanamSaathi-AI) — AI-Powered Matrimony Platform

**The problem:** Indian arranged marriage timelines are brutally slow.

- Parents shortlist candidates → horoscope checks → family meetings → **1–2 months gone**
- Boy and girl finally meet → compatibility evaluation → **another 3–4 months**
- Dating apps offer speed, but shallow profiles ("foodie 🍕 wanderlust ✈️") and authenticity issues make them a poor fit for serious relationships

**What I built:** An AI matchmaking system that compresses a 6+ month process into **weeks** by replacing manual compatibility guesswork with semantic AI analysis.

**How it works under the hood:**

- **FAISS vector search** with semantic embeddings matches candidates on values, lifestyle, and personality — not just demographic filters. Result: relationship assessments that previously took months now complete in days (internal benchmark: ~85% faster end-to-end)
- **Redis write-behind caching** absorbs read/write spikes during high-traffic match discovery, reducing direct database load by ~50% in load testing
- **JWT authentication** + **WebSocket-based progress tracking** keep users informed in real time during AI analysis — no page refreshes, no guessing

**Stack:** Python · FastAPI · FAISS · Redis · WebSockets · JWT · PostgreSQL

---

### [GenApply](https://github.com/Bharath-Ramamurthy/gen-apply) — AI Resume & Cover Letter Automation

**The problem:** Job applications are broken at scale.

- **Time sink:** 45–60 minutes per application × 50–100 applications = hundreds of hours lost
- **Ineffective:** Generic templates yield low response rates; manual customization doesn't scale
- **Error-prone:** Repetitive copy-paste workflows lead to fatigue and mistakes that kill opportunities

**What I built:** A multi-agent AI system that automates the full application workflow while keeping the user in control at every step.

**The workflow:**

1. **Analyze 🔍** — AI parses the job description and extracts key requirements
2. **Tailor 📝** — Resume is customized using **RAG-based semantic matching** against the JD
3. **Write ✍️** — Personalized cover letter generated in seconds, not minutes
4. **Review 📧** — Draft handed back to the user before anything is sent

**Result:** 45–60 minutes → **5–8 minutes per application** (~85% time reduction, measured across test runs)

**Key engineering decisions:**

- **Multi-agent orchestration** — Specialized agents handle discrete stages (parsing, tailoring, writing) rather than a single monolithic LLM call. This isolates failures and makes the system easier to debug and extend
- **Auto-Diagnostic Agent** — Monitors for runtime issues and attempts autonomous resolution before surfacing errors to the user. Improved reliability significantly (~60% reduction in failed runs during internal testing)
- **Factory pattern for LLM providers** — Swapping between OpenAI, Mistral, Gemini, and Hugging Face requires zero application-layer changes. I chose this pattern specifically to avoid vendor lock-in and enable cost optimization per use case

**Stack:** Python · FastAPI · LangChain · RAG · FAISS · OpenAI · Mistral · Gemini · Hugging Face

---

## 💼 What I've Shipped in Production

- **₹1.5M+ in annual cost savings** delivered through backend optimizations and GenAI automation at [Company Name]
- Production RAG pipelines, LLM integrations, and REST APIs serving real users — not just demos
- Systems designed with caching, async processing, and vector search at their core

---

## 🛠 Tech Stack

**Backend:** Python · FastAPI · Flask · REST APIs · WebSockets  
**AI/ML:** LangChain · RAG · FAISS · OpenAI · Mistral · Gemini · Hugging Face  
**Data & Storage:** PostgreSQL · Redis · Vector Databases  
**Auth & Infra:** JWT · Docker · Git  

---

## 📫 Let's Talk

If you're building something ambitious in backend infrastructure or GenAI and want an engineer who ships — reach out.

[LinkedIn](https://linkedin.com/in/YOUR_HANDLE) · [Email](mailto:YOUR_EMAIL)
