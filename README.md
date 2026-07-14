<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=12&height=200&section=header&text=Md%20Kamran%20S%20Rashid&fontSize=40&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Continual%20Learning%20%C2%B7%20Machine%20Unlearning%20%C2%B7%20Compliance%20Systems&descAlignY=62&descSize=17" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=650&lines=Research+Intern+%40+Indian+Statistical+Institute%2C+Kolkata;Data+%26+Graph+Intelligence+Lead+%40+Nia;Primary+Author+%E2%80%94+IEEE+TQCEBT+2026" alt="Typing SVG"/>

<br/>

<img src="https://komarev.com/ghpvc/?username=kamran-rashid&label=Profile+Views&color=7AA2F7&style=for-the-badge"/>
<img src="https://img.shields.io/badge/Bengaluru%2C%20India-🇮🇳-7AA2F7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Open%20To-Research%20%26%20Startup%20Collabs-7AA2F7?style=for-the-badge"/>

</div>

<br/>

## 👤 About Me

```ts
interface Researcher {
  name: string;
  degree: string;
  university: string;
  supervisor: string;
  currentWork: string[];
  publication: string;
  mindset: string;
}

const kamran: Researcher = {
  name: "Md Kamran S Rashid",
  degree: "B.Sc. Computer Science & Statistics (Hons.)",
  university: "Christ (Deemed to be University), Bengaluru — '27",
  supervisor: "Dr. Malay Bhattacharyya, Indian Statistical Institute, Kolkata",
  currentWork: [
    "TPMC — online machine-unlearning framework for streaming classification",
    "Nia — Living Compliance Graph for India's DPDP Act",
    "DASR — unifying non-stationary RL, continual learning & unlearning",
  ],
  publication: "IEEE TQCEBT 2026 — Primary Author (Scopus-track)",
  mindset: "Technically defensible, novel combinations over incremental work.",
};
```

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

**Problem:** Streaming classifiers accumulate stale, irrelevant memory and have no verifiable way to forget it on demand.

**Approach:** A Three-Gate criterion (relevance, population, uncertainty) that proactively deletes temporally-stale clusters with **verified exact deletion (L1 = 0)** at O(1) cost vs. O(N) retraining.

| Layer | Tech |
|---|---|
| Drift scoring | Sliced Wasserstein Distance |
| Backbone | 512–768-dim embeddings |
| Baselines beaten | EWC (+33.56%), multi-head (+28.89%) |

</td><td width="33%" valign="top">

### ⚖️ Nia
*Compliance OS for India's DPDP Act — In Progress*

**Problem:** No unified system connects codebases, infrastructure, vendors, and legal text to trace DPDP compliance gaps.

**Approach:** A "Living Compliance Graph" combining syntax-aware code parsing with an LLM classification filter — moving beyond brittle keyword search — plus a clause-extraction engine and automated PR-ready remediation drafts.

| Layer | Tech |
|---|---|
| Graph | Living Compliance Graph |
| Detection | Code parsing + LLM filter |
| Output | Auto-drafted DPDP clause language |

</td><td width="33%" valign="top">

### 🎲 DASR
*Drift-Aware Selective Replay — RL Research, In Progress*

**Problem:** Non-stationary RL, continual learning, and machine unlearning have evolved as disconnected subfields despite sharing a core problem: what to keep, and what to forget.

**Approach:** A unified replay-management framework with a three-gate retention/migration/deletion criterion, backed by a derived sublinear dynamic-regret bound.

| Layer | Tech |
|---|---|
| Scoring | Sliced Wasserstein Distance |
| Bound | O(V^{1/3}T^{2/3}) dynamic regret |
| Eval | MuJoCo HalfCheetah, contextual bandits vs. 5 baselines |

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

| Category | Technologies |
|---|---|
| Languages | Python · R · Java · C · SQL · PHP |
| ML / Deep Learning | PyTorch · TensorFlow · XGBoost · Scikit-learn · Focal Loss Networks |
| Research Methods | Continual Learning · Machine Unlearning · Uncertainty Quantification · Optimal Transport |
| NLP / LLMs | DistilBERT · Claude API · prompt-keyed clustering |
| Data & Graph Systems | Neo4j · FastAPI · Supabase · PCA · Sliced Wasserstein Distance |
| APIs & Integration | arXiv · Semantic Scholar · HuggingFace · AIKosh REST APIs |
| Tools | Git/GitHub · VS Code · Tableau · Excel |

<br/>

## 🌱 Currently Exploring

| Area | Focus |
|---|---|
| 🔁 Non-Stationary RL | Bandits under drift, regret bounds |
| 🧹 RL Unlearning | Forgetting guarantees in policy learning |
| 🕸️ Graph Compliance Reasoning | Legal-clause reconciliation over knowledge graphs |
| 📉 Distributional Drift | Optimal transport for high-dim feature spaces |

<br/>

## 🎖️ Leadership & Involvement

| Role | Organization | Focus |
|---|---|---|
| Overall Head | Labyrinth (CS Dept. Club) | Technical event planning & team management |
| Market Link (Head) | StaDa — Statistics & Data Science Club | Marketing & inter-department fest coordination |
| Session Moderator | Leadership Chair | Peer leadership-development sessions |
| Course Representative | Centre for Social Action | Sustainability initiatives |
| Peer Educator (Team Lead) | Centre for Counselling & Health Services | Mental health & relationships sessions |
| Core Committee Member | Centre for Artificial Intelligence | AI Conclave & technical coordination |
| Core Member | Apex — Centre for Quantitative Finance | Data analysis & economic research |

<br/>

## 📜 Certifications

| Certificate | Issuer |
|---|---|
| Python for Data Science | Infosys Springboard |
| Advanced R Programming for Data Analytics in Business | Swayam NPTEL |
| Artificial Intelligence | Infosys Springboard |
| A Comprehensive Learning Path to Become a Data Scientist in 2025 | Analytics Vidhya |

<br/>

## 🏆 Awards

| Achievement |
|---|
| Award of Excellence — Outstanding Performance, Class 12 Boards |
| 100% marks in Computer Science, ISC Examination |
| Merit Scholarship & Extracurricular Scholarship, 2024 |
| 1st Place — Department Fest Statistics Event |
| 2nd Place — Department Data Analysis Event |

<br/>

## 🎓 Academic

| | |
|---|---|
| **Degree** | B.Sc. Computer Science & Statistics (Hons.) |
| **University** | Christ (Deemed to be University), Bengaluru |
| **GPA** | 3.8 / 4 |
| **Graduating** | 2027 |
| **School** | Calcutta Boys' School, Kolkata |
| **ISC (Class XII)** | 93.75% |
| **ICSE (Class X)** | 85.2% |

<br/>

## 📈 GitHub Analytics

<div align="center">
<img height="165em" src="https://github-readme-stats.vercel.app/api?username=kamran-rashid&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7AA2F7&icon_color=BB9AF7&text_color=C0CAF5"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kamran-rashid&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7AA2F7&text_color=C0CAF5"/>

<br/>

<img src="https://streak-stats.demolab.com?user=kamran-rashid&theme=tokyonight&hide_border=true&background=0D1117&ring=7AA2F7&fire=F7768E&currStreakLabel=A9B1D6"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=kamran-rashid&theme=tokyonight&no-frame=true&margin-w=8&row=1&column=6"/>
</div>

> To activate the animated contribution snake below: create a repo named exactly `kamran-rashid` with `.github/workflows/snake.yml` running [Platane/snk](https://github.com/Platane/snk) on a schedule.

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
