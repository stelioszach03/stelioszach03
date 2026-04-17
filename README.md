<h1 align="center">Stelios Zacharioudakis</h1>

<p align="center">
  <strong>Machine Learning Engineer & Researcher</strong><br>
  BSc Computer Science · NKUA · Athens, Greece<br>
  <em>Open to ML/DL roles in Canada</em>
</p>

<p align="center">
  <a href="https://stelioszach.com"><img src="https://img.shields.io/badge/Portfolio-stelioszach.com-0a192f?style=for-the-badge&logo=google-chrome&logoColor=64ffda" alt="Portfolio"/></a>
  <a href="https://stelioszach.com/papers/cegvr-verifiable-reasoning.pdf"><img src="https://img.shields.io/badge/Latest_Paper-CEGVR-8b2f20?style=for-the-badge&logo=arxiv&logoColor=white" alt="Paper"/></a>
  <a href="https://www.linkedin.com/in/stylianos-georgios-zacharioudakis-47024428a"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:stelios@stelioszach.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=stelioszach03&show_icons=true&theme=github_dark&hide_border=true&count_private=true&hide_title=true&hide_rank=false" width="49%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=stelioszach03&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D" width="49%"/>
</p>

---

I build **production ML systems** — not notebooks. Every project below is deployed on a VPS with Docker, CI/CD, Prometheus metrics, and a live interactive demo. My research spans **deep learning**, **graph neural networks**, **LLM inference**, and **formal verification**.

### Core Skills

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/GNN-Graph_Neural_Networks-7C3AED?style=flat-square"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square"/>
  <img src="https://img.shields.io/badge/Z3_SMT-Solver-8b2f20?style=flat-square"/>
  <img src="https://img.shields.io/badge/spaCy-NER-09A3D5?style=flat-square&logo=spacy&logoColor=white"/>
  <img src="https://img.shields.io/badge/vLLM-EAGLE--3-7C3AED?style=flat-square"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/NVIDIA_A100-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
</p>

---

### 📄 Research Papers

| Paper | Area | Key Result | Links |
|:------|:-----|:-----------|:------|
| **CEGVR** | LLM + Formal Verification | **90.6% certified accuracy** vs 40.2% one-shot — 50-point lift via Z3 UNSAT-core feedback | [PDF](https://stelioszach.com/papers/cegvr-verifiable-reasoning.pdf) · [Code](https://github.com/stelioszach03/llm-smt-verifiable-reasoning) · [Demo](https://stelioszach.com/llm-smt-verifiable-reasoning/) |
| **DynaDiff-VLBI** | Radio Interferometric Imaging | Benchmark for dynamic EHT reconstruction *(submitted to MNRAS)* | [PDF](https://stelioszach.com/papers/dynadiff-vlbi.pdf) · [Code](https://github.com/stelioszach03/DynaDiff-VLBI) |
| **TrustQueryNet** | Medical Image Classification | 83.5% acc on HAM10000 with noise-robust ConvNeXt + calibrated selective prediction | [PDF](https://stelioszach.com/papers/trustquerynet.pdf) · [Code](https://github.com/stelioszach03/TrustQueryNet) |
| **Speculative Decoding** | LLM Inference Optimization | 1.46× speedup with vLLM + EAGLE-3 on A100 80 GB | [PDF](https://stelioszach.com/papers/colab-speculative-decoding-speed-lab.pdf) · [Code](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab) |

---

### 🚀 Production ML Systems — all live with interactive demos

<table>
<tr>
<td width="50%" valign="top">

#### [Graph Fraud GNN](https://stelioszach.com/graph-fraud-command-center/)
Hybrid heuristic + PyTorch GNN scoring engine. 14 graph features, 457 req/s, p95 = 3.3 ms. Live Simulate + Score.

`PyTorch` `GNN` `FastAPI` `Grafana`

</td>
<td width="50%" valign="top">

#### [Realtime Fraud Guard](https://stelioszach.com/realtime-fraud-guard/)
Streaming cross-channel scoring (payments/SMS/email). ROC-AUC 1.0 on holdout. Live scoring widget.

`Kafka` `gRPC` `Redis Streams` `Prometheus`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [AML Graph Investigator](https://stelioszach.com/aml-graph-investigator/)
Graph-native AML triage. 3K nodes, 51K edges, ROC-AUC 0.87. Live node investigator.

`LightGBM` `NetworkX` `Neo4j` `React`

</td>
<td width="50%" valign="top">

#### [NYC Subway Anomaly](https://stelioszach.com/nyc-subway-anomaly/)
Real-time GTFS-RT ingestion + online ML. 1000+ stations tracked. Click route pills to filter live.

`River` `TimescaleDB` `Next.js` `Mapbox`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [CEGVR — LLM+SMT](https://stelioszach.com/llm-smt-verifiable-reasoning/)
90.6% certified accuracy on linear-arithmetic SMT. 7500 eval runs on Qwen3-30B-A3B / A100.

`Z3 Solver` `vLLM` `Qwen3-30B` `A100`

</td>
<td width="50%" valign="top">

#### [DeID Privacy Studio](https://stelioszach.com/aegis-deid/)
PHI/PII redaction with 20+ entity types. Per-label mask/hash/redact policies. Interactive studio.

`spaCy` `NER` `Celery` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [DoubleX Ledger](https://stelioszach.com/doublex-ledger/)
SERIALIZABLE double-entry ledger. Idempotent postings, FX settlement, 94% coverage. Live idempotency widget.

`SQLAlchemy` `PostgreSQL` `Prometheus` `Grafana`

</td>
<td width="50%" valign="top">

#### [LimitForge RLS](https://stelioszach.com/limitforge-rls/)
4-algorithm rate limiter (token bucket / fixed / sliding / concurrency). Atomic Redis Lua. Live burst tester.

`Redis` `Lua` `PostgreSQL` `FastAPI`

</td>
</tr>
</table>

---

<p align="center">
  <em>Every project above is <strong>deployed and live</strong> with interactive demos — not just code in a repo.</em>
</p>

<p align="center">
  <a href="https://stelioszach.com"><strong>🌐 stelioszach.com</strong></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/stylianos-georgios-zacharioudakis-47024428a"><strong>💼 LinkedIn</strong></a> &nbsp;·&nbsp;
  <a href="mailto:stelios@stelioszach.com"><strong>📧 stelios@stelioszach.com</strong></a>
</p>
