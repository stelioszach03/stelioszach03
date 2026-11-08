# Stelios Zacharioudakis

**Machine Learning Engineer | Applied AI & ML Systems**

I’m a Machine Learning Engineer specializing in applied AI, LLM applications and ML systems. As Head Engineer, I led architecture and delivery of AsklepiosMed. My work spans multilingual NLP, RL-based agents, reproducible GPU inference evaluation and monitored data services.

[Portfolio](https://stelioszach.com/) · [CV](https://stelioszach.com/cv/) · [LinkedIn](https://www.linkedin.com/in/stelios-zach) · [Contact](mailto:stelios@stelioszach.com)

## Selected systems

### AsklepiosMed — Applied AI and production engineering

Led architecture and delivery of a production platform unifying member services, publishing and association administration. Engineered React interfaces, Express APIs and PostgreSQL workflows with role-based access controls; owned application deployment and service operations. **Head Engineer: June 2022–July 2026.**

The current project includes **multilingual NLP workflows** for announcement drafting, email preparation, proofreading, text improvement and Greek-to-English, Russian and Simplified Chinese translation. Structured JSON outputs, terminology and integrity checks, bounded retries, fallback handling, editorial review and usage controls support the application. These capabilities describe continued project work after July 2026.

[Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md) · [Public platform](https://asklepiosmed.org/)

### ForgeRL / ForgeBench — Inspectable LLM agent evaluation

Built a sandboxed code-repair harness, durable spending controls and a trajectory explorer. The frozen transfer pilot records **162 episodes across 27 miniature tasks and six policies**; a separate four-seed follow-up records **1,296 attempts** on the exposed catalog. Prompts, patches, verification and costs remain inspectable. Language-model weights stay unchanged; the studies do not establish a general adaptive-routing advantage.

[Live evidence explorer](https://stelioszach.com/demos/forgerl/) · [Source and protocol](https://github.com/stelioszach03/forgerl)

### Inference Systems Lab — 16,384 measured requests

Designed and ran a controlled vLLM study across **RTX 4090 and A100 80GB**, two Qwen2.5 model sizes and four repeats. Shared-prefix cached/uncached throughput ratios were **1.23–1.47× at concurrency 32**. Published throughput, latency, GPU telemetry and exact-output comparisons. The original 1,536-request pilot remains separately documented. Output parity fails; measured throughput ratios are not lossless speedup or answer-quality claims.

[Two-GPU results](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab/blob/main/artifacts/factorial-serving-v1/RESULTS.md) · [Source and reproduction](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab)

### MTA-Scan — Live data and chronological evaluation

Built public GTFS-Realtime ingestion, a FastAPI/Mapbox workspace, bounded historical storage and automated 15/30-minute proxy evaluation. **November 7, 2026 audit:** 44 verified daily exports, a rolling 28-day evaluation, 8,060 retained five-minute windows and 99.44% complete/fresh coverage. Forecasts are gated by history, comparable cohorts, freshness and evaluation age. A separate official MTA service-alert collector now archives revisions and supplies route-filtered context through a read-only API. The target is future feed-predicted arrival spacing, not observed train passages or validated incident detection.

[Live monitor](https://stelioszach.com/demos/mta-scan/) · [Coverage audit](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection/blob/main/docs/COLLECTION_COVERAGE.md) · [Deployed source](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan)

### MRI reconstruction — PyTorch and generative models

Reimplemented a published score-based reconstruction method, converted a pretrained Flax checkpoint and evaluated uncertainty and retrospective domain shift. The thesis reports reference PSNR agreement **within 0.15 dB on 256 BraTS slices** at 4×, 8× and 24× undersampling. The evidence companion adds reproducible tables, plots and independent CPU ensemble diagnostics. Original method and prior credited; no clinical validation.

[Thesis and methods](https://stelioszach.com/#mri) · [Evidence and diagnostics](https://github.com/stelioszach03/mri-reconstruction-evidence)

## Background

**BSc in Computer Science — National and Kapodistrian University of Athens, June 2026.** Degree: Very Good. BSc thesis: Excellent, **10/10**; deposited September 2026.

Ongoing independent research explores verifier-guided self-improvement and continual learning for coding agents, including task selection, procedural memory, retention and transfer. My world-model work studies imagination horizons, critic stability and policy evaluation. These research directions are unpublished; controlled evaluations and failed hypotheses remain part of the record.

**ML & AI:** Python, PyTorch, reinforcement learning, AI agents, world models, self-improvement experiments, NLP, generative models, vLLM, NumPy, SciPy, scikit-learn and experimental evaluation.

**Engineering:** FastAPI, React, Node.js/Express, PostgreSQL, Redis, Linux, Docker, Git and automated testing.

Based in the New York City metropolitan area. Interested in Machine Learning Engineer, Applied AI and ML Systems roles with ownership of implementation, evaluation and reliable deployment.

[Full evidence index](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/docs/EVIDENCE_INDEX.md) · [Secondary DeID review tool](https://stelioszach.com/demos/deid/)
