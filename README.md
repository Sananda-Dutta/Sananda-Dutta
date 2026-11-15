<!-- ═══════════════ HEADER ═══════════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Sananda%20Dutta&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Data%20Science%20%E2%80%A2%20ML%20Systems%20%E2%80%A2%20GenAI%20%E2%80%A2%20APIs&descSize=18&descAlignY=58" width="100%" alt="header"/>

<p align="center">
  <a href="https://github.com/Sananda-Dutta/Sananda-Dutta">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=36BCF7&center=true&vCenter=true&width=720&lines=Building+production-grade+ML+systems;Shipping+AI+APIs+people+can+actually+use;Currently+building+OmniRAG+%E2%80%94+multi-modal+RAG;B.Tech+Data+Science+%40+NIET+(2024%E2%80%932028);Open+to+internships+%26+collaborations+%F0%9F%9A%80" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sananda-dutta-71a26a346/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://codolio.com/profile/SanandaDutta"><img src="https://img.shields.io/badge/Codolio-Profile-FF6F00?style=for-the-badge&logo=codeforces&logoColor=white"/></a>
  <a href="https://huggingface.co/SanandaDutta"><img src="https://img.shields.io/badge/🤗%20HuggingFace-SanandaDutta-FFD21E?style=for-the-badge&logoColor=black"/></a>
  <img src="https://komarev.com/ghpvc/?username=Sananda-Dutta&label=Profile%20Views&color=2c5364&style=for-the-badge"/>
</p>

---

## 👨‍💻 About Me

```python
class Sananda:
    role      = "Third-year B.Tech Data Science @ NIET, Greater Noida"
    focus     = ["Production ML", "GenAI / RAG", "APIs & Backend", "MLOps"]
    building  = ["OmniRAG", "Website Category Classifier API"]
    goal      = "Top product-company roles + a monetizable SaaS API"
    fun_fact  = "I rebuilt a classifier from 59% to 82.2% accuracy by fixing data leakage, not by changing the model."
```

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Website Category Classifier (WCC)
DistilBERT-powered API that classifies any URL into **11 categories** (News, Education, Gaming, Health, Technology, …).

- 🎯 **82.2%** honest test accuracy (leakage fixed)
- 🧩 Microservices: Playwright scraper + inference service + FastAPI gateway
- 🛡️ Bot-block fallback via Browserless
- 💸 Monetized on **RapidAPI** (Free / Basic / Pro)
- 🔌 Chrome extension for quick testing

![](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![](https://img.shields.io/badge/Transformers-FFD21E?logo=huggingface&logoColor=black)
![](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)

🔗 [Model on HuggingFace](https://huggingface.co/SanandaDutta/website-category-distilbert) · [Repo](https://github.com/Sananda-Dutta/REPO_NAME_HERE)

</td>
<td width="50%" valign="top">

### 🧠 OmniRAG — Multi-Modal AI Knowledge Assistant
Production-grade RAG chatbot over **PDF, DOCX, images, web URLs and audio**, with citation-backed answers.

- 🔎 Hybrid retrieval (dense + BM25) with re-ranking
- 🧵 Query rewriting, memory, tool calling
- 📏 RAG evaluation (Ragas / DeepEval) + observability
- ⚙️ FastAPI · PostgreSQL · Qdrant/pgvector · Celery
- 🎨 React + TypeScript + Tailwind frontend

![](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

🔗 [Repo](https://github.com/Sananda-Dutta/REPO_NAME_HERE) · *work in progress*

</td>
</tr>
</table>

<details>
<summary><b>🏗️ Click to see how WCC works (architecture)</b></summary>

```mermaid
flowchart LR
    A[Client / RapidAPI / Chrome Extension] --> B[FastAPI Gateway]
    B --> C{Scrape OK?}
    C -- yes --> D[Playwright Scraper]
    C -- bot-blocked --> E[Browserless Fallback]
    D --> F[Clean + Weight Text]
    E --> F
    F --> G[DistilBERT Classifier]
    G --> H[Category + Confidence]
    H --> B
```

**Lessons learned:** train/inference mismatch capped early accuracy at ~59%; rebuilding the dataset with real page content and removing seed-word leakage gave an honest 82.2%.

</details>

<details>
<summary><b>📌 Pinned repo cards (auto-updating)</b></summary>
<br/>

<!-- Replace REPO_NAME_HERE with your real repo names -->
<a href="https://github.com/Sananda-Dutta/REPO_NAME_HERE">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sananda-Dutta&repo=website-category-classifier&theme=tokyonight&hide_border=true"/>
</a>
<a href="https://github.com/Sananda-Dutta/REPO_NAME_HERE_2">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sananda-Dutta&repo=Omnirag&theme=tokyonight&hide_border=true"/>
</a>

</details>

---

## 🛠️ Tech Stack

**Languages & ML**

<img src="https://skillicons.dev/icons?i=python,js,ts,java,cpp,sql&theme=dark"/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,pandas,numpy&theme=dark"/>

**Backend, Data & DevOps**

<img src="https://skillicons.dev/icons?i=fastapi,postgres,redis,docker,git,github,githubactions,linux,gcp&theme=dark"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,tailwind,html,css&theme=dark"/>

<details>
<summary><b>🧪 More tools I use</b></summary>

`HuggingFace Transformers` · `DistilBERT` · `LIME` · `Playwright` · `Qdrant` · `pgvector` · `Celery` · `Pydantic` · `SQLAlchemy` · `Ragas` · `Langfuse` · `RapidAPI` · `UptimeRobot` · `Google Cloud Run`

</details>

---

## 📊 GitHub Analytics

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=Sananda-Dutta&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sananda-Dutta&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Sananda-Dutta&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Sananda-Dutta&theme=tokyo-night&hide_border=true&area=true"/>
</p>

### 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sananda-Dutta/Sananda-Dutta/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sananda-Dutta/Sananda-Dutta/output/github-snake.svg"/>
    <img alt="snake" src="https://raw.githubusercontent.com/Sananda-Dutta/Sananda-Dutta/output/github-snake.svg"/>
  </picture>
</p>

### 🏆 Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Sananda-Dutta&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=10"/>
</p>

---

## 🧩 Coding Profiles

<p align="center">
  <a href="https://codolio.com/profile/SanandaDutta">
    <img src="https://img.shields.io/badge/View%20my%20full%20DSA%20%2B%20Dev%20portfolio%20on%20Codolio%20→-FF6F00?style=for-the-badge"/>
  </a>
</p>

---

## 🤝 Let's Connect

<p align="center">
  I'm looking for <b>internships / placements</b> in ML, GenAI and backend engineering.<br/>
  Reach out on <a href="https://www.linkedin.com/in/sananda-dutta-71a26a346/">LinkedIn</a> — happy to chat about ML systems, RAG, or API products.
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" alt="footer"/>
