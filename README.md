# Stelios Zacharioudakis

ML engineer in Athens. BSc Computer Science, NKUA — expected Jun 2026.

**Now:** Head Engineer since Jun 2022 at the Pancyprian Medical Association of Paphos, building
[asklepiosmed.org](https://asklepiosmed.org) — the production platform for a 480-doctor member
registry. Express + PostgreSQL + React 18 + iOS monorepo, deployed on systemd + nginx.

## Selected work

Every number below comes from an artifact committed in the repo it belongs to.

| Project | Measured result | Evidence in repo |
|---|---|---|
| [**TrustQueryNet**](https://github.com/stelioszach03/TrustQueryNet) — noise-robust skin-lesion classification | **83.5% ± 0.6** on HAM10000 over 5 seeds, ECE 0.0445 — and **56.9%** under external shift to ISIC 2019 | per-seed CSVs + resolved configs + paired significance tests |
| [**EuroSAT benchmark**](https://github.com/stelioszach03/eurosat-ssl-benchmark) — 7 learning paradigms on one split (coursework) | LoRA reaches **98.22%** while training **0.36%** of parameters (310,292 / 86,108,948), 3.7× faster than full fine-tuning | saved notebook cell outputs |
| [**Speculative decoding lab**](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab) — vLLM + EAGLE-3, A100 80 GB | **1.39× aggregate** latency speedup (1.46× on math prompts). The Transformers assisted-decoding path was **slower** than baseline in every configuration (best 0.35×) | `extracted_metrics.json` + per-config CSVs |
| [**NYC Subway anomaly detection**](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection) — live GTFS-RT, online ML (River) | **recall@20 = 1.00** vs 0.625 for the best of three baselines, at the highest false-alarm rate (0.030), on a 216-row / 3-incident replay set | `docs/generated/replay/metrics.json` |
| [**LimitForge RLS**](https://github.com/stelioszach03/limitforge-rls) — tenant-aware rate limiter, atomic Redis Lua | **92.57% line coverage** (536 / 579 lines), 79.55% branch | `coverage.xml` committed at repo root |

The research repos are solo, unpublished manuscripts — not peer-reviewed. Where a result is on
synthetic data or a small replay set, the repo says so.

## Stack

**ML** — PyTorch · HuggingFace · vLLM + EAGLE-3 · PEFT/LoRA · Z3 SMT · LightGBM · River · spaCy · CUDA / A100
**Systems** — Python · FastAPI · Node/Express · React · PostgreSQL · Redis · Kafka · Docker · GitHub Actions · Prometheus + Grafana · gRPC

## Contact

[stelioszach.com](https://stelioszach.com) · [LinkedIn](https://www.linkedin.com/in/stelios-zach) · [stelios@stelioszach.com](mailto:stelios@stelioszach.com)
