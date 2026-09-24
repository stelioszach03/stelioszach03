# Stelios Zacharioudakis

Machine learning research and software engineering, with a focus on generative reconstruction, world models and reliable evaluation.

[Portfolio](https://stelioszach.com/) · [CV](https://stelioszach.com/Stelios_Zacharioudakis_CV.pdf) · [Contact](mailto:stelios@stelioszach.com)

## Selected work

- **[MRI reconstruction thesis](https://stelioszach.com/#mri)** — PyTorch reimplementation of a published method, pretrained checkpoint conversion, uncertainty analysis and retrospective domain shift. The original method and prior are credited. Negative acquisition results and clinical limitations remain part of the study. The [v0.2.0 evidence companion](https://github.com/stelioszach03/mri-reconstruction-evidence/releases/tag/v0.2.0) adds independent NumPy ensemble diagnostics while preserving eight historical aggregate inputs. [Thesis PDF](https://stelioszach.com/documents/zacharioudakis-bsc-thesis-2026.pdf).
- **[ForgeRL / ForgeBench](https://github.com/stelioszach03/forgerl)** — Native v0.3 pilot explorer with 162 recorded episodes across 27 miniature tasks and six policies, plus the preserved v0.2 study. Inspect prompts, supplied files, patches, tests, model switches and accounted cost. Recorded replay is freely accessible without an API key or new inference. An optional live trial runs one published task with one GPT-OSS-20B call and isolated execution under shared spend limits; it is separate from benchmark evidence. Private research compares fixed-provider GPT-OSS models; model weights remain unchanged and no general policy advantage is claimed. [Evidence and trial interface](https://stelioszach.com/demos/forgerl/) · [Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/forgerl.md).
- **[AsklepiosMed](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md)** — a donated medical-association platform. My pro bono Head Engineer role ran from June 2022 to July 2026; current capabilities, including subsequent development, are documented separately. Private application source and member data remain private. [Public association website](https://asklepiosmed.org/).
- **[MTA-Scan](https://stelioszach.com/demos/mta-scan/)** — public NYC Subway feeds, a Mapbox workspace and autonomous historical collection. Deployed workers refresh five-minute features/status and run hourly chronological 15/30-minute evaluation of a **future feed-predicted arrival-spacing proxy**. Stable platform cohorts, availability timestamps and simple baselines keep the target explicit. Current measurements are early feasibility, not longitudinal evidence or validated incident prediction; a constructed replay remains separate. [Deployed adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan) · [Temporal protocol](https://github.com/stelioszach03/NYC-Subway-Anomaly-Detection/blob/main/docs/TEMPORAL_EVALUATION.md).

## Recorded research and systems evidence

**[ForgeBench prospective transfer pilot](https://github.com/stelioszach03/forgerl/blob/main/artifacts/forgebench/v0.3-pilot1/report/pilot-report.md):** all 162 frozen episodes completed. On 18 primary tasks in six fresh families, supervised return solved 17; fitted-Q, strong-only and escalation solved 16; cheap and hand-written solved 15. One seed and small authored programs do not establish superiority. Shared VERIFY is not learned, and all failed final tests remain in the report.

**[Inference Systems Lab — controlled GPU results](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab/blob/main/artifacts/controlled-pilot-v1/RESULTS.md):** 1,536 measured requests on one RTX 4090, three paired cache OFF/ON repeats, four concurrency levels and direct GPU telemetry. Raw evidence includes output mismatches; no lossless or answer-quality claim. **[MRI evidence package v0.2.0](https://github.com/stelioszach03/mri-reconstruction-evidence):** eight unchanged historical aggregate records with reproducible CPU tables/plots, a source-license audit and independent NumPy tools for ensemble spread, residual filtering and error association. These diagnostics neither rerun reconstruction nor establish calibrated clinical uncertainty; solver and medical data remain excluded.

**Preserved ForgeBench v0.2 study:** 300 evaluation episodes and 180 controller-training episodes, with [v0.2.1 software reference](https://github.com/stelioszach03/forgerl/releases/tag/v0.2.1). Its 50-task catalog spans ten authored repository families; the held-out test split covers two. Provider failures are retained, and the results do not establish a general advantage for adaptive routing. [Technical report](https://forge.stelioszach.com/api/forgebench/download/technical-report.pdf) · [Evidence dashboard](https://forge.stelioszach.com/).

**MTA temporal coverage at September 24, 2026, 21:45 UTC:** 21 hours 15 minutes, 256 five-minute windows and 39 evaluable route/direction groups. This is an early feasibility snapshot, not weeks of validated forecasting. Public proxy forecasts remain behind a 14-day history gate plus freshness and comparable-coverage checks. Missing seasonal measurements stay null, and model selection uses validation rather than test data.

## Three selected live demos

| Open the interface | What to inspect | Deployed source |
| --- | --- | --- |
| **[ForgeRL / ForgeBench](https://stelioszach.com/demos/forgerl/)** | Explore the native 162-episode/six-policy v0.3 pilot and preserved v0.2 trajectories. Recorded replay is free and makes no inference calls; the optional one-task live trial is separately budget-limited | [Standalone service and protocol](https://github.com/stelioszach03/forgerl) |
| **[MTA-Scan](https://stelioszach.com/demos/mta-scan/)** | Inspect live feeds/stations, freshness and autonomous 15/30-minute proxy-evaluation readiness; early feasibility and constructed replay are explicitly separate | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan) |
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
