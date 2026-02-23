# Hi, I'm Bharath R 👋

**Software Engineer** with **4 years of experience** building scalable backend systems and production-ready GenAI applications.

I specialize in **Python · FastAPI · Flask · REST APIs · LLMs · RAG pipelines** — with a focus on solving real-world problems at scale, not just prototyping ideas.

> Currently open to backend / GenAI engineering roles. [Let's connect →](https://www.linkedin.com/in/bharath-ramamurthy/)

---

## 🚀 Featured Projects

### [JanamSaathi AI](https://github.com/Bharath-Ramamurthy/JanamSaathi-AI): AI-Powered Matrimony Platform

**The problem:** Indian arranged marriage timelines are brutally slow.

- Parents shortlist candidates → horoscope checks → family meetings → **1–2 months gone**
- Boy and girl finally meet → compatibility evaluation → **another 3–4 months**
- Dating apps offer speed, but shallow profiles ("foodie 🍕 wanderlust ✈️") and authenticity issues make them a poor fit for serious relationships

**What I built:** An AI matchmaking system that compresses a 6+ month process into **weeks** by replacing manual compatibility guesswork with semantic AI analysis.

**How it works under the hood:**

- **FAISS vector search** with semantic embeddings matches candidates on values, lifestyle, and personality — not just demographic filters. Result: relationship assessments that previously took months now complete in days (internal benchmark: ~85% faster end-to-end)
- **Redis write-behind caching** absorbs read/write spikes during high-traffic match discovery, reducing direct database load by ~50% in load testing
- **JWT authentication** + **WebSocket-based progress tracking** keep users informed in real time during AI analysis — no page refreshes, no guessing

**Stack:**

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115.0-009688.svg?style=flat&logo=FastAPI&logoColor=white)](https://fastapi.tiangolo.com)
[![FAISS](https://img.shields.io/badge/FAISS-1.7.3-000000.svg?style=flat&logo=python&logoColor=white)](https://github.com/facebookresearch/faiss)
[![LLMs](https://img.shields.io/badge/LLMs-Transformers-6F42C1.svg?style=flat&logo=HuggingFace&logoColor=white)](https://huggingface.co/docs/transformers/index)
[![RAG](https://img.shields.io/badge/RAG-Retrieval--Augmented%20Generation-FF6600.svg?style=flat&logo=OpenAI&logoColor=white)](https://www.researchgate.net/publication/363693134_Retrieval-Augmented_Generation)
[![Redis](https://img.shields.io/badge/Redis-7.0-DC382D.svg?style=flat&logo=Redis&logoColor=white)](https://redis.io)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-336791.svg?style=flat&logo=PostgreSQL&logoColor=white)](https://www.postgresql.org)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-F4F4F4.svg?style=flat&logo=SQLAlchemy&logoColor=black)](https://www.sqlalchemy.org)
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B.svg?style=flat&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.5+-0175C2.svg?style=flat&logo=dart&logoColor=white)](https://dart.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

### [GenApply](https://github.com/Bharath-Ramamurthy/gen-apply): AI Resume & Cover Letter Automation

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

**Stack:** 
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.30.0-FF4B4B.svg?style=flat&logo=Streamlit&logoColor=white)](https://streamlit.io)
[![LangChain](https://img.shields.io/badge/LangChain-0.1.16-6F42C1.svg?style=flat&logo=HuggingFace&logoColor=white)](https://www.langchain.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-latest-0099FF.svg?style=flat&logo=OpenAI&logoColor=white)](https://www.langgraph.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-1.29.0-412991.svg?style=flat&logo=OpenAI&logoColor=white)](https://openai.com)
[![Transformers](https://img.shields.io/badge/Transformers-4.41.2-FF6F61.svg?style=flat&logo=HuggingFace&logoColor=white)](https://huggingface.co/docs/transformers/index)
[![HuggingFace-Hub](https://img.shields.io/badge/HuggingFace_Hub-0.23.0-FB8C00.svg?style=flat&logo=HuggingFace&logoColor=white)](https://huggingface.co/docs/huggingface_hub)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-F4F4F4.svg?style=flat&logo=SQLAlchemy&logoColor=black)](https://www.sqlalchemy.org)


---


## 📫 Let's Talk

If you're building something ambitious in backend infrastructure or GenAI and want an engineer who ships - reach out.

[LinkedIn](https://www.linkedin.com/in/bharath-ramamurthy/) · [Email](mailto:bharath.workmail@gmail.com)
