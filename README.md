# Stelios Zacharioudakis

Machine learning research and software engineering, with a focus on generative reconstruction, world models and reliable evaluation.

[Portfolio](https://stelioszach.com/) · [CV](https://stelioszach.com/Stelios_Zacharioudakis_CV.pdf) · [Contact](mailto:stelios@stelioszach.com)

## Selected work

- **[MRI reconstruction thesis](https://stelioszach.com/#mri)** — PyTorch reimplementation of a published method, pretrained checkpoint conversion, uncertainty analysis and retrospective domain shift. The original method and prior are credited. Negative acquisition results and clinical limitations remain part of the study. [Thesis PDF](https://stelioszach.com/documents/zacharioudakis-bsc-thesis-2026.pdf).
- **[ForgeRL / ForgeBench](https://github.com/stelioszach03/forgerl)** — 50 authored coding scenarios across 10 miniature repository families, five routing policies, isolated evaluation and a read-only evidence dashboard. Inspect recorded prompts, supplied files, patches, tests, model switches and accounted cost. Private research compares GPT-OSS 20B and 120B through a fixed-provider OpenRouter profile; model weights remain unchanged. Catalog size and measured coverage are separate, with no general policy advantage claimed. [Evidence dashboard](https://stelioszach.com/demos/forgerl/) · [Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/forgerl.md).
- **[AsklepiosMed](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md)** — a donated medical-association platform. My pro bono Head Engineer role ran from June 2022 to July 2026; current capabilities, including subsequent development, are documented separately. Private application source and member data remain private. [Public association website](https://asklepiosmed.org/).
- **[MTA-Scan](https://stelioszach.com/demos/mta-scan/)** — public NYC Subway feed observations, an interactive map, explicit freshness states and snapshot export. A separate constructed replay exposes sensitivity and false alarms; it is not official incident ground truth or validated incident prediction. [Deployed adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan).

## Recorded research and systems evidence

**[ForgeBench prospective transfer pilot](https://github.com/stelioszach03/forgerl/blob/main/artifacts/forgebench/v0.3-pilot1/report/pilot-report.md):** all 162 frozen episodes completed. On 18 primary tasks in six fresh families, supervised return solved 17; fitted-Q, strong-only and escalation solved 16; cheap and hand-written solved 15. One seed and small authored programs do not establish superiority. Shared VERIFY is not learned, and all failed final tests remain in the report.

**[Inference Systems Lab — controlled GPU results](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab/blob/main/artifacts/controlled-pilot-v1/RESULTS.md):** 1,536 measured requests on one RTX 4090, three paired cache OFF/ON repeats, four concurrency levels and direct GPU telemetry. Raw evidence includes output mismatches; no lossless or answer-quality claim. **[MRI evidence package](https://github.com/stelioszach03/mri-reconstruction-evidence):** eight historical aggregate records with reproducible CPU tables/plots and a source-license audit; solver and medical data remain excluded.

**ForgeBench v0.2 study complete:** 300 evaluation episodes and 180 controller-training episodes; latest software release [v0.2.1](https://github.com/stelioszach03/forgerl/releases/tag/v0.2.1). The held-out test split covers two repository families. Provider failures are retained, and the results do not establish a general advantage for adaptive routing. [Technical report](https://forge.stelioszach.com/api/forgebench/download/technical-report.pdf) · [Evidence dashboard](https://forge.stelioszach.com/).

## Three selected live demos

| Open the interface | What to inspect | Deployed source |
| --- | --- | --- |
| **[ForgeRL / ForgeBench](https://stelioszach.com/demos/forgerl/)** | Compare recorded policies, filter the 50-task catalog and inspect complete trajectories, patches, tests and accounted cost; browsing makes no inference requests | [Standalone service and protocol](https://github.com/stelioszach03/forgerl) |
| **[MTA-Scan](https://stelioszach.com/demos/mta-scan/)** | Filter live public observations, inspect a station and export a snapshot; keep constructed replay evaluation separate | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan) |
| **[DeID text review](https://stelioszach.com/demos/deid/)** — secondary tool | Review detections, keep or apply suggestions and redact missed spans; human review does not guarantee anonymity | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/deid) |

The [DeID engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/deid-review.md) documents exact output reconstruction, Unicode-safe review and executable regressions. Use supplied synthetic text, not personal or confidential data. These are selected interfaces; other projects and their limitations remain accessible through the repository list.

## Ongoing research

**World-model learning and evaluation — ongoing, unpublished research.** I study imagination horizons, critic stability and policy selection in latent world models. Controlled simulator comparisons have produced task-dependent outcomes, including failed controller and selection hypotheses. Limited task, world-model and training-seed coverage constrains generalization; this is not physical-robot deployment. [Research overview](https://stelioszach.com/#world-models).

## Previous experience

**Former Head Engineer — Paphos Medical Association · June 2022–July 2026 · Pro bono.** I developed and donated AsklepiosMed to support the association's member services. My role ended in July 2026. The current platform, including subsequent development, is described separately in the [case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md).

## Background and tools

**BSc in Computer Science**, National and Kapodistrian University of Athens — **June 2026**.

- **Research:** Python, PyTorch, NumPy, SciPy, model-based reinforcement learning, generative models and experimental evaluation.
- **Software:** FastAPI, Node.js/Express, React, PostgreSQL, Redis, Linux, Docker and automated testing.

I am interested in machine learning research and engineering opportunities where careful experiments and reliable implementation matter.
