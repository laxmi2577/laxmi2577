<!-- ══ HEADER ══ -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0d1117,50:0f2747,100:1f6feb&text=Laxmiranjan%20Sahu&fontColor=c9d1d9&fontSize=40&fontAlignY=38&desc=AI%2FML%20Intern%20%40%20Infosys%20PMIS%20%7C%20RAG%20%7C%20ML%20Systems&descSize=18&descAlignY=58&animation=fadeIn" alt="Header" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1800&color=58A6FF&center=true&vCenter=true&width=900&lines=0.85+F1+%7C+0.92+Recall%4010+%7C+82%25+Accuracy+in+Prod;PyTorch+%C2%B7+RAG+Pipelines+%C2%B7+LLM+Fine-tuning;OCI+Triple+Certified+%7C+AI%2FML+Intern+%40+Infosys+PMIS;SIH+Champion+%C2%B7+700%2B+LeetCode+%C2%B7+PyPI+Published" alt="Typing Animation" />
</div>

<div align="center">
  <a href="https://linkedin.com/in/laxmiranjan">
    <img src="https://img.shields.io/badge/LinkedIn-laxmiranjan-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://laxmiranjansahu.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-1f6feb?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:laxmiranjan444@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-laxmiranjan444%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://drive.google.com/file/d/1_l8r8N8c5nrdRG4R4PyUt5QPCKQ1MfZi/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-PDF-30363d?style=flat-square&logo=googledrive&logoColor=white" alt="Resume" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=laxmi2577&style=flat-square&color=58a6ff&label=Profile+Views" alt="Profile Views" />
</div>

---

<!-- ══ WHOAMI ══ -->
## `$ whoami`

```python
class LaxmiranjanSahu:
    name = "Laxmiranjan Sahu"
    github = "laxmi2577"
    role = "AI/ML Intern @ Infosys (PMIS)"
    program = "PMIS (Prestigious National Program)"
    location = "Bhubaneswar, Odisha, India"
    education = "B.Tech CSE, BPUT | CGPA: 8.2/10 | 2020-2024"
    open_to = ["AI/ML Engineering", "Data Science", "Applied GenAI", "ML Systems"]
    building = ["Aura AI", "FlagGuard"]
    methods = ["statistical modeling", "A/B testing", "time series"]
    workflow = ["EDA", "ETL pipelines", "evaluation-first deployment"]
    current_focus = [
        "RAG systems with measurable retrieval quality",
        "latency-aware model serving with FastAPI and Docker",
        "static analysis for feature-flag safety using Z3 + tree-sitter",
    ]
    links = {
        "portfolio": "https://laxmiranjansahu.vercel.app/",
        "linkedin": "https://linkedin.com/in/laxmiranjan",
        "email": "laxmiranjan444@gmail.com",
        "resume": "https://drive.google.com/file/d/1_l8r8N8c5nrdRG4R4PyUt5QPCKQ1MfZi/view?usp=sharing",
    }

    def ship(self):
        return "Models with metrics, APIs, and clear failure modes."
```

---

<!-- ══ METRICS ══ -->
## Production ML Metrics

Measured systems. Real evaluation numbers. Production constraints included.

| Model/System | Task | Dataset | Score | Prod Notes |
| --- | --- | --- | --- | --- |
| PyTorch CNN | Emotion classification | FER-2013 (35K images) | 0.85 weighted F1 | 7-class emotion model behind Face DJ and mood-aware flows |
| all-MiniLM-L6-v2 + Supabase pgvector | RAG retrieval | 10K+ docs | 0.92 Recall@10 | Semantic retrieval layer for AI Coach and search |
| MIT AST Model | Audio classification | AudioSet | 0.459 mAP | Audio-aware inference for soundtrack and interaction features |
| FastAPI Lifespan optimization | Cold-start reduction | HF Spaces backend | 2.4s -> 430ms | 82% latency reduction through preload and startup orchestration |
| Gemini 2.5 Flash-Lite | LLM token efficiency | Aura AI inference | 400x ROI vs GPT-4o | Chosen for production cost control without degrading UX |

---

<!-- ══ PROJECTS ══ -->
## Selected Systems

### Aura AI

![Status](https://img.shields.io/badge/Status-Complete-238636?style=flat-square) [![Repo](https://img.shields.io/badge/Repo-aura--platform-30363d?style=flat-square&logo=github&logoColor=white)](https://github.com/laxmi2577/aura-platform) [![Live Frontend](https://img.shields.io/badge/Live-Frontend-111827?style=flat-square&logo=vercel&logoColor=white)](https://aura-ai-liard-eight.vercel.app) [![Live Backend](https://img.shields.io/badge/Live-Backend-1f6feb?style=flat-square)](https://laxmiranjan444-aura-ml-brain.hf.space)

Aura AI is a multimodal wellness platform built with Next.js 16, TypeScript, TailwindCSS, FastAPI, PyTorch, Supabase pgvector, Gemini 2.5 Flash-Lite, Hugging Face Spaces, and Vercel. The stack combines a FER-2013 CNN, AudioSet classification, and 10K+ document retrieval to deliver a 0.85 weighted F1 emotion model, 0.92 Recall@10 retrieval, 0.459 mAP audio classification, 430ms cold-start, and 400x token-cost ROI versus GPT-4o. The backend also handles 50+ concurrent requests/sec.

Features: Face DJ, Binaural Brainwaves, Sound Mixer, AI Coach, Semantic Search, Voice Control, 3D Galaxy Visualizer, Smart Timer.

```
[ Next.js 16 UI on Vercel ]
             |
             v
[ FastAPI runtime on Hugging Face Spaces ]
      |                |                 |
      v                v                 v
[ PyTorch CNN ]  [ MIT AST Model ]  [ MiniLM + pgvector ]
  FER-2013         AudioSet            Supabase RAG
      \                |                 /
       \               |                /
        +-------- [ Gemini 2.5 Flash-Lite ] --------+
                               |
                               v
        Face DJ / AI Coach / Semantic Search / Smart Timer
```

Why this design:
- Split the Next.js frontend on Vercel from GPU-bound inference on Hugging Face Spaces so UI deploys stay fast and model workloads stay isolated.
- Used all-MiniLM-L6-v2 with Supabase pgvector to maximize Recall@10 on 10K+ documents without adding heavyweight retrieval latency.
- Preloaded models inside FastAPI lifespan hooks because interactive cold-start mattered more than headline benchmark numbers.

### FlagGuard

![Status](https://img.shields.io/badge/Status-60%25_WIP-f78166?style=flat-square) [![Repo](https://img.shields.io/badge/Repo-flagguard-30363d?style=flat-square&logo=github&logoColor=white)](https://github.com/laxmi2577/flagguard) [![PyPI](https://img.shields.io/pypi/v/flagguard?style=flat-square&label=PyPI&color=58a6ff)](https://pypi.org/project/flagguard/)

FlagGuard is an enterprise-grade AI feature-flag static analysis engine inspired by the Knight Capital $440M failure. It proves feature-flag safety before deployment with Z3 Boolean constraints, scans Python and JavaScript via tree-sitter, translates solver failures into plain-English PR feedback with Gemma 2B through Ollama, and exposes 31 REST endpoints behind FastAPI, JWT, SQLAlchemy, and RBAC roles. The package is published on PyPI and currently spans 47 commits.

```bash
pip install flagguard
```

```
[ GitHub PR / Local Repo ]
            |
            v
[ tree-sitter AST scanner ]
      |                 |
      v                 v
[ Python AST ]     [ JavaScript AST ]
      \                 /
       \               /
        +--> [ Z3 SMT constraints ] --> [ Safety proof / counterexample ]
                                              |
                                              v
                           [ Ollama + Gemma 2B explanation layer ]
                                              |
                                              v
                [ FastAPI + SQLAlchemy + JWT + RBAC + 31 REST endpoints ]
                                              |
                                              v
                [ Gradio dashboard ] [ GitHub Actions gate ] [ PyPI ]
```

Why this design:
- Encoded flag relationships as Boolean constraints in Z3 to target zero false positives instead of heuristic lint noise.
- Chose tree-sitter over regex scanning so Python and JavaScript analysis stays language-aware and extensible to Go, Java, and Ruby.
- Kept Gemma 2B local through Ollama so solver failures become readable PR comments without sending sensitive repo logic to external APIs.

Roadmap: Go, Java, and Ruby AST support, VS Code extension, SAML SSO, and SARIF output for GitHub Advanced Security.

---

<!-- ══ EXPERIENCE ══ -->
## Experience

```
Infosys | AI/ML Intern | PMIS (Prestigious National Program)            Jul 2025 - Present
Bhubaneswar, Odisha, India

- Trained 5+ scikit-learn classification models and reached 82% accuracy.
- Deployed models with Docker and REST APIs, improving inference speed by 35%.
- Built automation pipelines across 100K+ records and reduced processing time by 40%.
- Reduced client forecasting error by 15% MAPE using ARIMA time-series models.
- Delivered weekly Matplotlib and Seaborn EDA reports to stakeholders.
- Collaborated with 8 engineers in an Agile delivery environment.
```

---

<!-- ══ STACK ══ -->
## Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)

**ML/AI**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NLTK](https://img.shields.io/badge/NLTK-154F7D?style=flat-square) ![Hugging%20Face%20Transformers](https://img.shields.io/badge/Hugging%20Face%20Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![all-MiniLM-L6-v2](https://img.shields.io/badge/all--MiniLM--L6--v2-4B5563?style=flat-square)

**GenAI & RAG**  
![LangChain](https://img.shields.io/badge/LangChain-121D33?style=flat-square) ![Supabase%20pgvector](https://img.shields.io/badge/Supabase%20pgvector-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![Gemini%202.5%20Flash](https://img.shields.io/badge/Gemini%202.5%20Flash-4285F4?style=flat-square&logo=google&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-111827?style=flat-square) ![Gemma%202B](https://img.shields.io/badge/Gemma%202B-4F46E5?style=flat-square&logo=google&logoColor=white) ![Z3%20SMT%20Solver](https://img.shields.io/badge/Z3%20SMT%20Solver-0F766E?style=flat-square) ![tree-sitter%20AST](https://img.shields.io/badge/tree--sitter%20AST-2E7D32?style=flat-square)

**Data Science**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Power%20BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) 

**Cloud/MLOps**  
![Oracle%20Cloud%20Infrastructure](https://img.shields.io/badge/Oracle%20Cloud%20Infrastructure-F80000?style=flat-square&logo=oracle&logoColor=white) ![Amazon%20S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![Amazon%20EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white) ![AWS%20Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub%20Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Hugging%20Face%20Spaces](https://img.shields.io/badge/Hugging%20Face%20Spaces-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Backend & Frontend**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Spring%20Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square) ![Next.js%2016](https://img.shields.io/badge/Next.js%2016-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind%20CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square)

---

<!-- ══ CERTIFICATIONS ══ -->
## Certifications

| Certification | Credential | Provider | Year |
| --- | --- | --- | --- |
| OCI 2025 Generative AI Professional | 1Z0-1127-25 | Oracle | 2025 |
| OCI 2025 Developer Professional | 1Z0-1084-25 | Oracle | 2025 |
| OCI 2025 AI Foundations Associate | 1Z0-1122-25 | Oracle | 2025 |
| Google Data Analytics: Foundations | Certificate | Coursera | 2025 |

---

<!-- ══ ACHIEVEMENTS ══ -->
## Achievements

| Achievement | Result | Signal |
| --- | --- | --- |
| Smart India Hackathon | 1st Place, Team Lead | Won against 50+ college teams |
| LeetCode | 700+ solved, Top 10% globally | Strong DSA and algorithmic foundation |
| College Coding Contest | 3rd Place | Consistent competitive problem solving |
| FlagGuard | Published on PyPI | Open-source package shipped to users |

---

<!-- ══ GITHUB ANALYTICS ══ -->
## GitHub Analytics

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=laxmi2577&show_icons=true&theme=github_dark&bg_color=0d1117&border_color=30363d&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e" alt="GitHub Stats" />
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=laxmi2577&layout=compact&theme=github_dark&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e" alt="Top Languages" />
  <img height="170em" src="https://streak-stats.demolab.com/?user=laxmi2577&background=0d1117&border=30363d&ring=58a6ff&fire=f78166&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&sideNums=c9d1d9&currStreakNum=c9d1d9" alt="GitHub Streak" />
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=laxmi2577&bg_color=0d1117&color=8b949e&line=58a6ff&point=f78166&area=true&hide_border=true" alt="Contribution Activity Graph" />
</div>

---

<!-- ══ FOOTER ══ -->
<div align="center">
  <p>Collaboration welcome on applied AI, RAG systems, and production ML tooling.</p>
  <img src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:1f6feb,50:0f2747,100:0d1117" alt="Footer" />
</div>
