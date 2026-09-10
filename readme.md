<div align="center">
  <img src="https://raw.githubusercontent.com/riju-talk/riju-talk/refs/heads/main/Black%20and%20Gray%20Minimalist%20LinkedIn%20Banner.png" width="100%" alt="Rijusmit Biswas"/>
</div>

<h1 align="center">Rijusmit Biswas</h1>

<p align="center">
  <b>Software and Machine Learning Engineer</b> — I turn research into software people can rely on.
</p>

<p align="center">
  New Delhi, India · Computer science at IIIT-Delhi, graduating September 2026
</p>

<p align="center">
  <a href="https://rijusmit.vercel.app">Portfolio</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/rijusmit-biswas/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:rijusmit.biswas@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://rijusmit.vercel.app/Rijusmit_Biswas_SDE_Resume.pdf">SDE résumé</a>
  &nbsp;·&nbsp;
  <a href="https://rijusmit.vercel.app/Rijusmit_Biswas_DS_Resume.pdf">DS résumé</a>
</p>

---

I build software end to end and stay with it once it goes live — the React screens, the API in
the middle, the database underneath, and the servers it runs on, plus machine learning when a
problem calls for it. So far that has meant taking a product from a rough idea to something live
on AWS, moving a running system onto a new stack with no visible outage, and building a portal
that more than 500 students use. On the research side I have shipped ML that people keep using:
**HorusLLM**, an evaluation harness my lab still runs to catch when a model starts answering
worse, and satellite-imagery pipelines for crop prediction. First author on the HorusLLM paper,
under review at AAAI 2027.

|  |  |  |  |  |
|:--:|:--:|:--:|:--:|:--:|
| **12+** | **1** | **13** | **1403** | **150+** |
| live deployments | first-author paper | models evaluated | Codeforces rating | LeetCode solved |

---

## Experience

| Role | Where | When | What |
|---|---|---|---|
| **Head of Product Development** | Student Council, IIIT-Delhi | 2025 – present | Built and shipped a student-services portal used by 500+ students; own the database, indexing, and the API eight engineers build against. Set up CI with automated tests and review the team's code. Replaced manual data entry with validating forms — ~60% less admin work and an end to a recurring class of bad records. |
| **Software Engineering Intern** | Shipzee | Mar – Aug 2026 | Shipped full-stack features on a live courier-aggregation product, screens through API to database. Led a move to a new stack planned so no one saw an outage. Chased cross-service production failures through logs and traces, and wrote contract tests around external integrations. |
| **AI Engineer & Undergraduate Researcher** | MIDAS Lab, IIIT-Delhi | May 2025 – Jan 2026 | Built HorusLLM, which scores model output against several notions of alignment and flags on its own when quality drops — cut fabricated answers ~20%, still in use. Reproducible pipelines over three datasets with retry and rate-limit handling. Trained models with LoRA/QLoRA at 4-bit. First author on the paper, under review at AAAI 2027. |
| **ML Research Intern** | Computational Social Science Lab, IIIT-Delhi | Jan – May 2025 | Built a parallel Google Earth Engine pipeline producing district-scale multi-channel inputs and segmentation masks. Compared CNN backbones on phenology, crop type, and yield under one shared setup. Measured cross-district drift with difference-in-differences and fixed-effects models. |
| **Data Science Intern** | Complex Systems Lab, IIIT-Delhi | Aug – Dec 2024 | Led a team of five on a 25-class classifier over messy real-world data (84.5% / 74.5% across splits) and traced the gap to a distribution shift. Built real-time data-visualisation web apps over open datasets. Ran reviews and mentored juniors. |
| **Open Source Contributor** | Meshery — Layer5 | 2025 | Bug reports, feature requests, documentation fixes, and pull requests; took part in code reviews. |

---

## Selected work

| Project | Type | Summary | Stack |
|---|---|---|---|
| [**Executive Career Agent**](https://github.com/riju-talk/executive-career-agent) | Agent swarm · desktop | Seven cooperating agents discover, de-duplicate, score, and tailor roles against a candidate's real résumé. Runs fully offline or against the live web; an anti-fabrication validator checks every claim against the master résumé. Ships an MCP server for Claude Desktop. | React · Electron · Node.js · MCP · LangChain |
| [**TURBO**](https://github.com/riju-talk/TURBO) | ML research | Independent reimplementation of Goel et al. (arXiv 2502.07391): fuses Vision Transformer image features with a modified BART text encoder for multimodal sarcasm explanation, trained on MORE+ and scored with BLEU / ROUGE / METEOR. | PyTorch · ViT · BART · Hugging Face |
| [**MineMEETS**](https://github.com/riju-talk/MineMEETS) | Multimodal retrieval | Turns images, text, and audio into embeddings behind one interface. Every step is dimension-checked and safe to rerun; Pinecone namespaces make reindex and rollback safe; tests and type checks run on every PR. | CLIP · Whisper · Pinecone · Docker · Pytest |
| [**Cross-Portfolio Default Risk**](https://github.com/riju-talk/loan-defaulter-prediction-study) | Data science research | Dual study of credit-default prediction across credit cards (UCI, 30K) and installment loans (LendingClub). 31+ engineered features, 13 calibrated models with SHAP and cost-sensitive thresholds. XGBoost 0.7769 ROC-AUC on cards; ~$18.7M estimated annual savings. | XGBoost · LightGBM · SHAP · Optuna |
| [**Quench++**](https://github.com/riju-talk/Quench-plus-plus) | Research tooling | Extends Indic reasoning benchmarks with injected bias and structured cause-and-effect chains in Boolean logic, so trustworthiness and reasoning can be measured repeatably. | Hugging Face · PyTorch · LoRA · QLoRA |
| [**DreamDOT**](https://github.com/riju-talk/DreamDOT) | Distributed backend | Creator platform with subscriptions and pay-per-view. A set of GraphQL services answer cross-service queries without request cascades; I set the service boundaries and schema contracts so teams could work in parallel on a shared graph. | GraphQL · Node.js · Microservices · MongoDB |
| [**Hostiggo**](https://github.com/riju-talk/Hostiggo-full-website) | Production SaaS | Idea to a product running on AWS: React front end, full backend, database, and servers, with CI and monitoring from the first week so releases stayed calm as usage grew. | Node.js · React · PostgreSQL · AWS |
| [**Flourish**](https://flourish-web-iota.vercel.app/) | Agentic service | Plant-care assistant. The FastAPI backend runs sequenced LLM tool calls against external APIs with retries and graceful fallbacks; Firebase handles auth and storage. | FastAPI · LangChain · Firebase · Docker |

---

## Skills

| Area | |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · C++ · SQL · C |
| **Backend & APIs** | Node.js · Express · FastAPI · REST & GraphQL · GraphQL federation · WebSockets · retries and rate limiting |
| **Frontend** | React · Next.js · Tailwind CSS · dashboards · live interfaces over WebSockets |
| **Infrastructure & delivery** | AWS · Docker · GitHub Actions · Linux · Vercel · Pytest · structured logging · static analysis |
| **Data & distributed systems** | PostgreSQL · MongoDB · Prisma · Pinecone · schema design · indexing · PySpark · Airflow · ETL |
| **Machine learning & research** | PyTorch · Hugging Face · LoRA & QLoRA · LangChain · RAG · CLIP & Whisper · Google Earth Engine |

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,cpp,pytorch,fastapi,nodejs,express,graphql,nextjs,react,tailwind,postgres,mongodb,redis,docker,aws,git,linux&theme=dark" alt="Tech stack"/>
</div>

---

## Publication

**HorusLLM: A Cross-Evaluation Protocol for Tri-Vector Alignment Interference**
Rijusmit Biswas (first author), A. G. Kumar, A. Anand, E. Cambria, Z. Wang, R. R. Shah
*Under review — AAAI 2027*

An evaluation harness that scores model output against several notions of alignment and flags on
its own when quality drops; the checking step cut fabricated answers by roughly 20%. Harness and
benchmarks released as open source.

---

## Activity

<div align="center">
  <img height="160" src="https://github-stats-extended.vercel.app/api?username=riju-talk&show_icons=true&hide_border=true&bg_color=00000000&title_color=2e6a4d&icon_color=2c637a&text_color=808a80" alt="GitHub stats"/>
  <img height="160" src="https://github-stats-extended.vercel.app/api/top-langs/?username=riju-talk&layout=compact&hide_border=true&bg_color=00000000&title_color=2e6a4d&text_color=808a80" alt="Top languages"/>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/riju-talk/riju-talk/assets/activity-graph.svg" width="95%" alt="Contribution activity"/>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/riju-talk/riju-talk/assets/trophy.svg" alt="Profile trophies"/>
</div>

---

## Contact

Open to SDE, MLE, Data Scientist, and Data Engineer roles and internships. Email is the quickest
way to reach me — a hard systems problem, a project worth doing, or a good research lead all welcome.

<a href="mailto:rijusmit.biswas@gmail.com">rijusmit.biswas@gmail.com</a>

---

<div align="center">
  <img src="https://github.com/riju-talk/riju-talk/blob/main/delhi_metro.jpg?raw=true" width="60%" alt="Original photography"/>
  <p><i>Delhi Metro — thinking visually, away from the editor.</i></p>
</div>
