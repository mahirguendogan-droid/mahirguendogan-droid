<div align="center">

# Mahir Gündoğan

**B.Sc. Software Engineering (2026) · Swiss citizen · Selzach, Solothurn 🇨🇭**

### I build *with* AI/ML — not just *with* the API key.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=6C7BFF&center=true&vCenter=true&width=560&lines=Autonomous+LLM+Agents;Semantic+Search+%26+Sentence-BERT;NLP+%7C+Vector+Retrieval+%7C+Computer+Vision;Statistics-first+ML+engineering)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mahir--guendogan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahir-guendogan)
[![Gmail](https://img.shields.io/badge/Email-mahir.guendogan%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mahir.guendogan@gmail.com)

> 🎯 **Open to AI/ML internships & junior roles in Switzerland** — Swiss citizen, no visa sponsorship required.

</div>

---

## About

I'm a Software Engineering graduate working at the intersection of **NLP, information retrieval, and applied machine learning**. Most of what I build comes down to one question: *how do you get a machine to understand what something actually means — and then prove that it does?*

That last part matters to me. Every project I ship comes with an evaluation harness: significance tests, baselines to beat, metrics that can embarrass me.

- 🤖 Built **AutoBiasAgent** — an autonomous LLM agent that audits any CSV for statistical and intersectional bias
- 🔍 Built a **semantic email retrieval engine** (SBERT + FAISS) benchmarked against BM25 — my BAU capstone
- 📊 Statistics-first: chi-squared, Cramér's V, Precision@K, MRR — not vibes
- 🗣️ Trilingual: **German** (native) · **English** (C2) · **Turkish** (native)
- 🎧 Outside the terminal: music production, international politics, sports

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![SBERT](https://img.shields.io/badge/Sentence--BERT-0B5FFF?style=for-the-badge&logo=readthedocs&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/LLM_Agents-412991?style=for-the-badge&logo=openai&logoColor=white)

**Data Science**

![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

**Backend & Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</div>

---

## Featured Projects

### ⚖️ [AutoBiasAgent](https://github.com/mahirguendogan-droid/bias_agent)
**An autonomous agent that flags biased columns in any CSV — for about $0.0005 a run.**

Upload a dataset, pick a target column, and it runs a four-phase pipeline on its own: per-column distribution analysis with **chi-squared** significance testing, **Cramér's V** chain-of-thought synthesis, intersectional bias assessment across column pairs, and an independent **LLM-as-judge** pass before anything is reported. Findings come out risk-stratified CRITICAL → LOW, with columns in correlated pairs escalated automatically, plus plain-English explanations of *why*.

`Python` · `GPT-4o-mini` · `SciPy` · `Gradio` — 3–5 LLM calls per full audit, deployed behind a Gradio UI.

### 🧠 [Semantic Email Retrieval System](https://github.com/mahirguendogan-droid/semantic-email-retrieval)
**Email search by meaning, not keyword match.** *BAU capstone — team of 4.*

Sentence-BERT embeddings indexed in **FAISS**, benchmarked over a 500-email corpus with hand-built relevance judgments against a **BM25** keyword baseline. Includes a model comparison mode across MiniLM / MPNet / Paraphrase and a full evaluation harness.

`Python` · `Sentence-Transformers` · `FAISS` · `BM25` · `FastAPI` — measured on **Precision@K, Recall@K, MRR** and query latency.

---

## Education

**B.Sc. Software Engineering** — Bahçeşehir University, Istanbul · *2022 – 2026*
Focus on software development, algorithms and core computer science.

`Data Science with Python` `Data Analysis with R` `Natural Language Processing` `Computer Vision / AI Image Detection` `Data Structures & Algorithms` `OOP` `Databases`

Member of the **BAU Software Club** since 2025 — workshops on programming tools and development practices.

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mahirguendogan-droid&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahirguendogan-droid&layout=compact&hide_border=true&theme=tokyonight&langs_count=6" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mahirguendogan-droid&hide_border=true&theme=tokyonight" />

</div>

---

<div align="center">

### 📬 Let's talk

Looking for an **AI/ML internship in Switzerland**, or just want to argue about retrieval metrics? Reach out.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahir-guendogan)
[![Email](https://img.shields.io/badge/Send_an_email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mahir.guendogan@gmail.com)
<img src="https://komarev.com/ghpvc/?username=mahirguendogan-droid&style=flat-square&color=6C7BFF" alt="profile views" />

</div>
