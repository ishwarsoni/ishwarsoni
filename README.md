<h1 align="center">Hi, I'm Ishwar Soni</h1>

<p align="center">
  <b>AI Engineer Intern @ Cosmos Consultant</b> · B.Tech CSE, Udaipur, India<br/>
  Building RAG / LLM applications and computer-vision pipelines that work on real data.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ishwar-soni-cs/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://ishwarsoni.me"><img src="https://img.shields.io/badge/Portfolio-ishwarsoni.me-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:ishwarsoni2917@gmail.com"><img src="https://img.shields.io/badge/Email-ishwarsoni2917@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/ishwarsoni"><img src="https://img.shields.io/github/followers/ishwarsoni?label=GitHub%20Followers&style=for-the-badge" alt="GitHub followers"/></a>
</p>

---

## About Me

- 🎓 B.Tech Computer Science, Techno India NJR Institute of Technology, Udaipur (2023–2027)
- 🤖 AI Engineer Intern at **Cosmos Consultant** (May 2026–present) — AI email features, REST API integrations, auth/session, prompt engineering and structured outputs
- 👁️ Former Computer Vision / Motion Processing Intern at **Semantic Labs** (Nov 2025–Jan 2026) — SMPL / SMPL-H and AMASS motion pipelines
- 🎯 Focus: RAG and LLM applications, applied AI, and computer vision
- 🌱 Currently learning: advanced ML engineering, agentic workflows, and evaluation

I like building things end-to-end — data in, a working system out, with tests and a clear README so someone else can actually run it.

---

## Featured Projects

### 🩺 OncoLink — Oncology Document Intelligence with RAG

AI-assisted oncology document intelligence and evidence-grounded clinical Q&A.

- Ingests PDF, DOCX and TXT records (referral letters, pathology reports, lab results, discharge summaries)
- Extracts structured clinical data with an LLM, validates it with Pydantic v2, and harmonises it across documents
- Surfaces cross-document conflicts instead of hiding them
- RAG answers are restricted to retrieved evidence, with validated citations back to the source document and page
- Hybrid retrieval: BM25 + dense embeddings + reciprocal rank fusion, BGE-small (384-d), ChromaDB
- 409 offline tests passing

**Tech:** `Python` `Streamlit` `NVIDIA Nemotron` `Sentence Transformers` `ChromaDB` `Pydantic`

> Educational / demonstration software only — not a medical device, and not for clinical decision-making.

🔗 [github.com/ishwarsoni/oncolink-ai](https://github.com/ishwarsoni/oncolink-ai)

---

### 🧹 DataCleanr — ML-Safe Data Cleaning Library

A Python library for cleaning messy, real-world datasets without corrupting labels.

- `clean()` never modifies the target column — target handling is explicit via `handle_target()`
- Smart datatype conversion, missing-value handling, outlier and skew handling with safeguards
- Conservative column selection — no aggressive drops or cascade deletion
- Every run returns a structured, transparent transformation report
- Validated on 50 datasets (classification + regression, real, synthetic noisy, and edge cases) — 0 failures, 0 target corruption

**Tech:** `Python` `Pandas` `NumPy` `Scikit-learn`

```bash
pip install datacleanr
```

🔗 [github.com/ishwarsoni/datacleaner](https://github.com/ishwarsoni/datacleaner)

---

### 🦴 BVH-to-SMPLH Pipeline — Motion Capture to SMPL-H

Utilities to convert BVH motion data into SMPL-H-style NPZ files, clean it up, and export it back for visualisation.

- BVH → NPZ conversion (52-joint SMPL-H-style output) and NPZ → BVH export for Blender / Unity / Unreal
- Grounding and foot-lock stabilisation to reduce floating and foot-sliding
- Batch BVH ↔ NPZ processing and MP4 motion visualisation
- Built from work on motion-capture cleaning — reorganised and extended here for independent use

**Tech:** `Python` `NumPy` `SciPy` `Matplotlib`

🔗 [github.com/ishwarsoni/bvh-to-smplh-pipeline](https://github.com/ishwarsoni/bvh-to-smplh-pipeline)

---

## Tech Stack

**Languages:** Python

**ML / Data:** NumPy · Pandas · Scikit-learn · Model Evaluation

**AI / LLM:** RAG · Prompt Engineering · LLM Integration · NVIDIA NIM · Sentence Transformers · ChromaDB

**Computer Vision:** SMPL · SMPL-H · Motion Analysis · AMASS

**Tools:** Git · GitHub · Streamlit · Jupyter · REST APIs

---

## Experience

**AI Engineer Intern — Cosmos Consultant** · May 2026–present · Hybrid
- AI email drafting / rewriting, REST API integrations, auth and session handling
- Prompt engineering, structured outputs, API error handling and testing

**Computer Vision / Motion Processing Intern — Semantic Labs** · Nov 2025–Jan 2026 · Remote
- SMPL / SMPL-H motion pipelines and AMASS data processing

---

## Certifications

- NVIDIA — RAG Agent Development
- Microsoft Applied Skills — Azure OpenAI

---

## GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=ishwarsoni&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ishwarsoni&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
  <img width="70%" src="https://streak-stats.demolab.com?user=ishwarsoni&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

---

## Let's Connect

I'm looking for AI Engineer / Generative AI / ML internship and entry-level roles in India, remote or hybrid.

- 💼 [LinkedIn](https://www.linkedin.com/in/ishwar-soni-cs/)
- 🌐 [ishwarsoni.me](https://ishwarsoni.me)
- 📧 ishwarsoni2917@gmail.com

> *"Building AI isn't about training models — it's about solving real-world problems."*
