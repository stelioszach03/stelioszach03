# Stelios Zacharioudakis

ML engineer in Athens. BSc Computer Science, NKUA — expected Jun 2026.

Head Engineer since Jun 2022 at the Paphos Medical Association, building [asklepiosmed.org](https://asklepiosmed.org) — the platform for a 480-doctor member registry, on an Express + PostgreSQL + React 18 + iOS monorepo.

**Live demos:** [SMT-verified reasoning](https://stelioszach.com/demos/smt-verify/) · [PHI redaction](https://stelioszach.com/demos/deid/) · [graph fraud scoring](https://stelioszach.com/demos/fraud-graph/) · [subway anomaly detection](https://stelioszach.com/demos/mta-scan/)

| Project | Measured result | Evidence in repo |
|---|---|---|
| [TrustQueryNet](https://github.com/stelioszach03/TrustQueryNet) | 83.5% ± 0.6 on HAM10000 over 5 seeds, ECE 0.0445 — and 56.9% under external shift to ISIC 2019 | per-seed CSVs, paired bootstrap CIs |
| [EuroSAT benchmark](https://github.com/stelioszach03/eurosat-ssl-benchmark) | LoRA reaches 98.22% training 0.36% of parameters (310,292 / 86,108,948), 3.7× faster than full fine-tuning | saved notebook cell outputs |
| [Speculative decoding lab](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab) | 1.39× aggregate latency speedup on A100 (1.46× on math prompts); the Transformers assisted path was slower than baseline in all 9 cells | `paper/data/*.csv` |
| [MTA-Scan](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection) | recall@20 1.00 vs 0.625 for the best of three baselines, at the highest false-alarm rate (0.030), on 216 rows / 3 incidents | `docs/generated/replay/metrics.json` |
| [LimitForge RLS](https://github.com/stelioszach03/limitforge-rls) | 92.57% line coverage (536 / 579), 79.55% branch | `coverage.xml` |

The research repos are solo, unpublished manuscripts — not peer-reviewed. Where a result rests on synthetic data or a small replay set, the repo says so.

**ML** — PyTorch · HuggingFace · vLLM + EAGLE-3 · PEFT/LoRA · Z3 · LightGBM · River · spaCy · CUDA / A100
**Systems** — Python · FastAPI · Node/Express · React · PostgreSQL · Redis · Kafka · Docker · GitHub Actions · Prometheus · gRPC

[stelioszach.com](https://stelioszach.com) · [LinkedIn](https://www.linkedin.com/in/stelios-zach) · [stelios@stelioszach.com](mailto:stelios@stelioszach.com)
