# Stelios Zacharioudakis

**Machine Learning Engineer · Reinforcement Learning · AI Agents · Self-Improving Systems**

I build and evaluate systems that learn from feedback. My focus spans reinforcement learning, self-improving agents, continual learning and world models, alongside multilingual NLP, generative models and production software engineering.

[Portfolio](https://stelioszach.com/) · [Machine Learning CV](https://stelioszach.com/Stelios_Zacharioudakis_CV.pdf) · [LinkedIn](https://www.linkedin.com/in/stelios-zach) · [Contact](mailto:stelios@stelioszach.com)

## Selected engineering and research

### AsklepiosMed — Applied AI and production engineering

Developed and donated a platform for the Paphos Medical Association, owning architecture, React interfaces, Express APIs, PostgreSQL and Linux deployment. **Head Engineer, pro bono: June 2022–July 2026.**

The current project includes **multilingual NLP workflows** for announcement drafting, email preparation, proofreading, text improvement and Greek-to-English, Russian and Simplified Chinese translation. Structured output validation, terminology checks, fallback behavior, editor review and usage controls support the application. Current capabilities include subsequent development beyond the former role.

[Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md) · [Public platform](https://asklepiosmed.org/)

### Inference Systems Lab — 16,384 measured requests

Designed and ran a controlled vLLM study across **RTX 4090 and A100 80GB**, two Qwen2.5 model sizes, cache modes, prefix patterns and four repeats. Published throughput, latency, GPU telemetry and exact-output comparisons. The original 1,536-request pilot remains separately documented. Output parity fails; measured throughput ratios are not lossless speedup or answer-quality claims.

[Two-GPU results](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab/blob/main/artifacts/factorial-serving-v1/RESULTS.md) · [Source and reproduction](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab)

### MRI reconstruction — PyTorch and generative models

Reimplemented a published score-based reconstruction method, converted a pretrained Flax checkpoint and evaluated uncertainty and retrospective domain shift. The thesis reports reference PSNR agreement **within 0.15 dB on 256 BraTS slices** at 4×, 8× and 24× undersampling. The evidence companion adds reproducible tables, plots and independent CPU ensemble diagnostics. Original method and prior credited; no clinical validation.

[Thesis and methods](https://stelioszach.com/#mri) · [Evidence and diagnostics](https://github.com/stelioszach03/mri-reconstruction-evidence)

### ForgeRL / ForgeBench — Inspectable LLM agent evaluation

Built a sandboxed code-repair harness, durable spending controls and a trajectory explorer. The frozen transfer pilot records **162 episodes across 27 miniature tasks and six policies**; a separate four-seed follow-up records **1,296 attempts** on the exposed catalog. Prompts, patches, verification and costs remain inspectable. Language-model weights stay unchanged; the studies do not establish a general adaptive-routing advantage.

[Live evidence explorer](https://stelioszach.com/demos/forgerl/) · [Source and protocol](https://github.com/stelioszach03/forgerl)

### MTA-Scan — Live data and chronological evaluation

Built public GTFS-Realtime ingestion, a FastAPI/Mapbox workspace, bounded historical storage and automated 15/30-minute proxy evaluation. **November 7, 2026 audit:** 44 verified daily exports, a rolling 28-day evaluation, 8,060 retained five-minute windows and 99.44% complete/fresh coverage. Forecasts are gated by history, comparable cohorts and freshness. The target is future feed-predicted arrival spacing, not observed train passages or validated incident detection.

[Live monitor](https://stelioszach.com/demos/mta-scan/) · [Coverage audit](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection/blob/main/docs/COLLECTION_COVERAGE.md) · [Deployed source](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan)

## Background

**BSc in Computer Science — National and Kapodistrian University of Athens, June 2026.** Degree: Very Good. BSc thesis: Excellent, **10/10**; deposited September 2026.

Ongoing independent research explores verifier-guided self-improvement and continual learning for coding agents, including task selection, procedural memory, retention and transfer. My world-model work studies imagination horizons, critic stability and policy evaluation. These research directions are unpublished; controlled evaluations and failed hypotheses remain part of the record.

**ML & AI:** Python, PyTorch, reinforcement learning, AI agents, world models, self-improvement experiments, NLP, generative models, vLLM, NumPy, SciPy, scikit-learn and experimental evaluation.

**Engineering:** FastAPI, React, Node.js/Express, PostgreSQL, Redis, Linux, Docker, Git and automated testing.

Based in the New York City metropolitan area. Interested in Machine Learning Engineer, Applied AI and ML Systems roles with ownership of implementation, evaluation and reliable deployment.

[Full evidence index](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/docs/EVIDENCE_INDEX.md) · [Secondary DeID review tool](https://stelioszach.com/demos/deid/)
