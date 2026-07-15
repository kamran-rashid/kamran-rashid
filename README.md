<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=12&height=200&section=header&text=Md%20Kamran%20S%20Rashid&fontSize=40&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Continual%20Learning%20%C2%B7%20Machine%20Unlearning%20%C2%B7%20Compliance%20Systems&descAlignY=62&descSize=17" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=680&lines=Research+Intern+%40+ISI+Kolkata;Data+%26+Graph+Intelligence+Lead+%40+Nia;Primary+Author+%E2%80%94+IEEE+TQCEBT+2026" alt="Typing SVG"/>

<br/>

<img src="https://komarev.com/ghpvc/?username=kamran-rashid&label=Profile+Views&color=7AA2F7&style=for-the-badge"/>
<img src="https://img.shields.io/badge/Bengaluru%2C%20India-🇮🇳-7AA2F7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Open%20To-Research%20%26%20Startup%20Collabs-7AA2F7?style=for-the-badge"/>

</div>

<br/>

## 👤 About Me

**Md Kamran S Rashid** — B.Sc. Computer Science & Statistics (Hons.), Christ (Deemed to be University), Bengaluru · Class of 2027

- 🔬 **Research Advisor:** Dr. Malay Bhattacharyya, Indian Statistical Institute, Kolkata
- 🧠 **Currently Building:** TPMC (machine unlearning) · Nia (DPDP compliance graph) · DASR (drift-aware replay)
- 📄 **Publication:** IEEE TQCEBT 2026 — Primary Author (Scopus-track)
- 💭 **Philosophy:** Technically defensible, novel combinations over incremental work

<br/>

## 🧭 What I Do

- 🔬 Design continual-learning & unlearning systems that survive **simultaneous drift and deletion constraints**
- 📐 Derive and validate theoretical guarantees — regret bounds, exact-deletion proofs, drift metrics
- 🕸️ Architect graph-based reasoning systems connecting code, infrastructure, and legal text
- 📊 Run rigorous ablation studies and report negative findings honestly, not just wins
- 🧾 Write for both academic venues (ECAI, AAAI) and early-stage product narratives (YC, incubators)

<br/>

## 💼 Experience

<table width="100%">
<tr><td width="10">🔵</td><td>

**Research Intern** · Indian Statistical Institute, Kolkata · *Feb 2026 – Present*
*Supervisor: Dr. Malay Bhattacharyya*

Designed and built **TPMC**, an online machine-unlearning framework clustering streaming data into temporally-cohesive prompt-keyed partitions, deleting stale clusters via a novel Three-Gate criterion. Redesigned the influence-scoring pipeline (Sinkhorn-OT → Sliced Wasserstein Distance), delivering a **33.56%** accuracy gain over EWC on HuffPost. Diagnosed method boundary conditions across four datasets, producing rigorous negative findings for ECAI 2026 / AAAI 2027 submission.

`PyTorch` `Sliced Wasserstein Distance` `Continual Learning` `Machine Unlearning`

</td></tr>
</table>

<br/>

## 🚀 Featured Work

<table width="100%">
<tr><td width="33%" valign="top">

### 🧠 TPMC
*Temporal Prompt-Aware Memory Consolidation — Research @ ISI Kolkata*

**Problem:** Streaming classifiers accumulate stale, irrelevant memory with no verifiable way to forget it on demand.

**Approach:** A Three-Gate criterion (relevance, population, uncertainty) that proactively deletes temporally-stale clusters with **verified exact deletion (L1 = 0)** at O(1) cost vs. O(N) retraining.

- Drift scoring: Sliced Wasserstein Distance
- Backbone: 512–768-dim embeddings
- +33.56% over EWC, +28.89% over multi-head baselines

</td><td width="33%" valign="top">

### ⚖️ Nia
*Compliance OS for India's DPDP Act — In Progress*

**Problem:** No unified system connects codebases, infrastructure, vendors, and legal text to trace DPDP compliance gaps.

**Approach:** A "Living Compliance Graph" combining syntax-aware code parsing with an LLM classification filter — moving beyond brittle keyword search — plus a clause-extraction engine and automated PR-ready remediation drafts.

- Detection: code parsing + LLM filter
- Reconciliation: clause-extraction engine
- Output: auto-drafted DPDP clause language

</td><td width="33%" valign="top">

### 🎲 DASR
*Drift-Aware Selective Replay — RL Research, In Progress*

**Problem:** Non-stationary RL, continual learning, and machine unlearning evolved as disconnected subfields despite sharing one core question: what to keep, and what to forget.

**Approach:** A unified replay-management framework with a three-gate retention/migration/deletion criterion, backed by a derived sublinear dynamic-regret bound.

- Scoring: Sliced Wasserstein Distance
- Bound: sublinear dynamic regret
- Eval: MuJoCo HalfCheetah, contextual bandits vs. 5 baselines

</td></tr>
</table>

<br/>

<table width="100%">
<tr><td>

### 📄 Empirical Evaluation of Confidence-Guided Selective Fusion
*IEEE TQCEBT 2026 — Primary Author*

**Problem:** Does fusing a calibrated tree model with a focal-loss neural network via confidence-based routing actually beat a single well-tuned model on imbalanced fraud data?

**Approach:** Ablations across threshold type, meta-feature combinations, and fusion-weight sensitivity on the 2013 Credit Card Fraud dataset, under strict anti-leakage protocols.

**Finding:** Confidence-guided fusion added only **ΔAUC-PR ≤ 0.0002** — evidence-based guidance against unnecessary model complexity. Presented at CHRIST University, Pune Lavasa; manuscript undergoing Scopus indexing.

</td></tr>
</table>

<br/>

## ⚡ Engineering Stack

**Languages**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>

**ML / Deep Learning**
<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Focal%20Loss%20Networks-6E40C9?style=for-the-badge"/>

**Research Methods**
<br/>
<img src="https://img.shields.io/badge/Continual%20Learning-6E40C9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Machine%20Unlearning-6E40C9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Uncertainty%20Quantification-6E40C9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Optimal%20Transport-6E40C9?style=for-the-badge"/>

**NLP / LLMs**
<br/>
<img src="https://img.shields.io/badge/DistilBERT-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Prompt--Keyed%20Clustering-6E40C9?style=for-the-badge"/>

**Data & Graph Systems**
<br/>
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/PCA-6E40C9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Sliced%20Wasserstein%20Distance-6E40C9?style=for-the-badge"/>

**APIs & Integration**
<br/>
<img src="https://img.shields.io/badge/arXiv-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white"/>
<img src="https://img.shields.io/badge/Semantic%20Scholar-1857B6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/AIKosh%20REST%20APIs-6E40C9?style=for-the-badge"/>

**Tools**
<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>

<br/>

## 🌱 Currently Exploring

- 🔁 **Non-Stationary RL** — bandits under drift, regret bounds
- 🧹 **RL Unlearning** — forgetting guarantees in policy learning
- 🕸️ **Graph Compliance Reasoning** — legal-clause reconciliation over knowledge graphs
- 📉 **Distributional Drift** — optimal transport for high-dim feature spaces

<br/>

## 🎖️ Leadership & Involvement

- **Overall Head**, Labyrinth (CS Dept. Club) — technical event planning & team management
- **Market Link (Head)**, StaDa — Statistics & Data Science Club — marketing & inter-department fest coordination
- **Session Moderator**, Leadership Chair — peer leadership-development sessions
- **Course Representative**, Centre for Social Action — sustainability initiatives
- **Peer Educator (Team Lead)**, Centre for Counselling & Health Services — mental health & relationships sessions
- **Core Committee Member**, Centre for Artificial Intelligence — AI Conclave & technical coordination
- **Core Member**, Apex — Centre for Quantitative Finance — data analysis & economic research

<br/>

## 📜 Certifications

- Python for Data Science — *Infosys Springboard*
- Advanced R Programming for Data Analytics in Business — *Swayam NPTEL*
- Artificial Intelligence — *Infosys Springboard*
- A Comprehensive Learning Path to Become a Data Scientist in 2025 — *Analytics Vidhya*

<br/>

## 🏆 Awards

- Award of Excellence — Outstanding Performance, Class 12 Boards
- 100% marks in Computer Science, ISC Examination
- Merit Scholarship & Extracurricular Scholarship, 2024
- 1st Place — Department Fest Statistics Event
- 2nd Place — Department Data Analysis Event

<br/>

## 🎓 Academic

- **Degree:** B.Sc. Computer Science & Statistics (Hons.)
- **University:** Christ (Deemed to be University), Bengaluru — GPA 3.8/4, graduating 2027
- **School:** Calcutta Boys' School, Kolkata
- **ISC (Class XII):** 93.75%
- **ICSE (Class X):** 85.2%

<br/>

## 📈 GitHub Analytics

<div align="center">

<br/>

<img src="https://streak-stats.demolab.com?user=kamran-rashid&theme=tokyonight&hide_border=true&background=0D1117&ring=7AA2F7&fire=F7768E&currStreakLabel=A9B1D6"/>

</div>

<div align="center">
<img src="https://raw.githubusercontent.com/kamran-rashid/kamran-rashid/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<br/>

## 🤝 Let's Connect

<div align="center">

<a href="mailto:mdkamransrashid@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/Md-Kamran-S-Rashid"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/kamran-rashid"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

<div align="center">

*"The models that survive aren't the ones that never forget — they're the ones that know exactly what to let go of."*

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=12&height=100&section=footer" width="100%"/>

</div>
