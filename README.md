<div align="center">

# Stelios Zacharioudakis

**Machine Learning Engineer & Researcher**

BSc Computer Science · National & Kapodistrian University of Athens

*Building end-to-end ML systems with Docker, CI, observability, and live demos — from research to reproducible pipelines.*

[![Portfolio](https://img.shields.io/badge/Portfolio-stelioszach.com-0a192f?style=for-the-badge&logo=google-chrome&logoColor=64ffda)](https://stelioszach.com)
[![Paper](https://img.shields.io/badge/Latest_Paper-CEGVR_90.6%25-8b2f20?style=for-the-badge&logo=arxiv&logoColor=white)](https://stelioszach.com/papers/cegvr-verifiable-reasoning.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stelios-zach)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:stelios@stelioszach.com)

<br>

**Open to junior ML / MLE roles** · 🇨🇦 Canadian work-authorized (open permit — no sponsorship needed) · Athens, Greece → Toronto

</div>

---

### 💼 Experience

| Role | Organization | Period | Impact |
|:-----|:-------------|:-------|:-------|
| Head Engineer | Paphos Medical Association | Jun 2022 – present | AsklepiosMed platform serving **480 doctors** · **99.5%** uptime over 12 months · deploy cycle 2 days → 15 minutes |
| Full-Stack Engineer | Medihyal Clinic | Jan 2025 – present | Booking platform, **200+ monthly reservations** · Groq LLM integration reduced manual review time by **80%** |

---

### 🧠 ML / DL

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/GNN-Graph_Neural_Networks-7C3AED?style=flat-square"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/vLLM-EAGLE--3-7C3AED?style=flat-square"/>
<img src="https://img.shields.io/badge/Z3-SMT_Solver-8b2f20?style=flat-square"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square"/>
<img src="https://img.shields.io/badge/spaCy-NER-09A3D5?style=flat-square&logo=spacy&logoColor=white"/>
<img src="https://img.shields.io/badge/River-Online_ML-1f6feb?style=flat-square"/>
<img src="https://img.shields.io/badge/NVIDIA_A100-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
</p>

### ⚙️ Engineering

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

---

### 📄 Research — 4 papers, all with code + reproducible pipelines

| | Paper | Status | Result | Links |
|:--|:------|:-------|:-------|:------|
| 🔬 | **CEGVR** — LLM + Z3 SMT Verifiable Reasoning | Manuscript · solo author | **90.6%** certified accuracy (+50 pts vs baseline) · 7 500 eval runs · Qwen3-30B-A3B on A100 | [📄 PDF](https://stelioszach.com/papers/cegvr-verifiable-reasoning.pdf) · [💻 Code](https://github.com/stelioszach03/llm-smt-verifiable-reasoning) · [🔬 Demo](https://stelioszach.com/llm-smt-verifiable-reasoning/) |
| 🔭 | **DynaDiff-VLBI** — Dynamic Radio Interferometric Imaging | Manuscript · solo author | EHT benchmark · 3D U-Net with test-time optimization | [📄 PDF](https://stelioszach.com/papers/dynadiff-vlbi.pdf) · [💻 Code](https://github.com/stelioszach03/DynaDiff-VLBI) |
| 🏥 | **TrustQueryNet** — Trustworthy Medical Image Classification | Manuscript · solo author | **83.5%** acc on HAM10000 · calibrated selective prediction · ConvNeXt-Tiny | [📄 PDF](https://stelioszach.com/papers/trustquerynet.pdf) · [💻 Code](https://github.com/stelioszach03/TrustQueryNet) |
| ⚡ | **Speculative Decoding Study** — LLM Inference Optimization | Manuscript · solo author | **1.46×** speedup · vLLM + EAGLE-3 · A100 80 GB | [📄 PDF](https://stelioszach.com/papers/colab-speculative-decoding-speed-lab.pdf) · [💻 Code](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab) |

---

### 🚀 Projects & Live Demos — 8 projects, all with live demos + CI pipelines

<table>
<tr>
<td width="50%" valign="top">

#### 🔴 [Graph Fraud GNN](https://stelioszach.com/graph-fraud-command-center/) · [![CI](https://github.com/stelioszach03/graph-fraud-command-center/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/graph-fraud-command-center/actions)
Hybrid heuristic + **PyTorch GNN** scoring. 14 graph-context features, **457 req/s**, p95 = 3.3 ms.

**Live:** Simulate transactions → Score → Threshold slider

`PyTorch` `GNN` `FastAPI` `Prometheus` `Grafana`

</td>
<td width="50%" valign="top">

#### 🛡️ [Realtime Fraud Guard](https://stelioszach.com/realtime-fraud-guard/) · [![CI](https://github.com/stelioszach03/realtime-fraud-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/realtime-fraud-guard/actions)
Streaming cross-channel scoring. **ROC-AUC 1.0** on holdout. Payments + SMS + email.

**Live:** Pick channel → Safe/Fraud preset → Score event

`Kafka` `gRPC` `Redis Streams` `Prometheus`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🕵️ [AML Graph Investigator](https://stelioszach.com/aegis-graph-aml/) · [![CI](https://github.com/stelioszach03/aml-graph-investigator/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/aml-graph-investigator/actions)
Graph-native AML triage. 3 061 nodes, 51 758 edges, **ROC-AUC 0.87**. Path-level explanations.

**Live:** Type node ID → Score + ego metrics + neighbors

`LightGBM` `NetworkX` `Neo4j` `React`

</td>
<td width="50%" valign="top">

#### 🚇 [NYC Subway Anomaly](https://stelioszach.com/nyc-subway-anomaly/) · [![CI](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection/actions)
Real-time GTFS-RT + **online ML** (River). **1 000+ stations**, 10s auto-refresh.

**Live:** Click route pills (1, A, N…) → Filter anomaly feed

`River` `TimescaleDB` `Next.js` `Mapbox`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧪 [CEGVR — LLM+SMT](https://stelioszach.com/llm-smt-verifiable-reasoning/) · [![CI](https://github.com/stelioszach03/llm-smt-verifiable-reasoning/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/llm-smt-verifiable-reasoning/actions)
**90.6%** certified accuracy via Z3 UNSAT-core feedback. 7 500 eval runs on A100.

**Live:** Interactive results viewer — click each arm → breakdown

`Z3 Solver` `vLLM` `Qwen3-30B-A3B` `A100`

</td>
<td width="50%" valign="top">

#### 🔒 [DeID Privacy Studio](https://stelioszach.com/aegis-deid/) · [![CI](https://github.com/stelioszach03/deid-privacy-studio/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/deid-privacy-studio/actions)
PHI/PII redaction. **20+ entity types**, per-label mask/hash/redact policies.

**Live:** Interactive studio with side-by-side redaction

`spaCy` `NER` `Celery` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📒 [DoubleX Ledger](https://stelioszach.com/doublex-ledger/) · [![CI](https://github.com/stelioszach03/doublex-ledger/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/doublex-ledger/actions)
SERIALIZABLE double-entry ledger. Idempotent postings, FX settlement, **94% coverage**.

**Live:** Post → Replay same key → Balance unchanged

`SQLAlchemy` `PostgreSQL` `Prometheus` `Grafana`

</td>
<td width="50%" valign="top">

#### ⚡ [LimitForge RLS](https://stelioszach.com/limitforge-rls/) · [![CI](https://github.com/stelioszach03/limitforge-rls/actions/workflows/ci.yml/badge.svg)](https://github.com/stelioszach03/limitforge-rls/actions)
4-algorithm rate limiter. Atomic **Redis Lua** scripts. **90% coverage**.

**Live:** Pick algorithm → Fire 1-25 parallel calls → Watch bars

`Redis` `Lua` `PostgreSQL` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🛰️ [EuroSAT DL Benchmark](https://github.com/stelioszach03/eurosat-ssl-benchmark)
**7 paradigms** compared: CNN, Transfer Learning, SimCLR, CLIP, LoRA. **98.37%** best accuracy.

**LoRA:** 98.22% with only **0.36%** trainable params

`PyTorch` `SimCLR` `CLIP` `LoRA` `EfficientNet`

</td>
<td width="50%" valign="top">

*More projects at [stelioszach.com](https://stelioszach.com) — including clinic systems, medical association platforms, and ongoing research.*

</td>
</tr>
</table>

---

<div align="center">

*Every project above has a live demo, CI pipeline, and reproducible setup.*

**[🌐 stelioszach.com](https://stelioszach.com)** · **[💼 LinkedIn](https://www.linkedin.com/in/stelios-zach)** · **[📧 stelios@stelioszach.com](mailto:stelios@stelioszach.com)**

</div>
