# Stelios Zacharioudakis

Machine learning research and software engineering, with a focus on world models, generative reconstruction and reliable evaluation.

[Portfolio](https://stelioszach.com/) · [CV](https://stelioszach.com/Stelios_Zacharioudakis_CV.pdf) · [Contact](mailto:stelios@stelioszach.com)

## A short technical tour

- **Research method:** [MRI thesis](https://stelioszach.com/#mri) — reimplementation, uncertainty and retrospective domain shift, with the original method credited.
- **Inspectable implementation:** [DeID review case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/deid-review.md) — exact output reconstruction, Unicode-safe human review, runnable regressions and explicit accuracy limits.
- **Previous engineering work:** [AsklepiosMed case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md) — pro bono Head Engineer role, June 2022–July 2026; the case study documents current project capabilities separately. Private source and member data stay private.

## Live demos

Open a working interface, then inspect the exact deployed adapter. Use the supplied synthetic examples; do not enter personal or confidential data.

| Open the demo | What it demonstrates | Deployed source |
| --- | --- | --- |
| **[Constraint verifier](https://stelioszach.com/demos/smt-verify/)** | Z3 checks a structured answer; no paid language-model call | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/smt-verify) |
| **[Text de-identification](https://stelioszach.com/demos/deid/)** | Inspect detections, apply/keep suggestions and manually redact missed spans; review remains required | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/deid) |
| **[Transaction graph explorer](https://stelioszach.com/demos/fraud-graph/)** | Graph features and scoring on synthetic, rule-labelled transactions | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/fraud-graph) |
| **[NYC subway monitor](https://stelioszach.com/demos/mta-scan/)** | Live public observations and a separate limited replay evaluation | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan) |

## Research

**World-model learning and evaluation — ongoing, unpublished research.** I investigate imagination horizons, critic stability and the relationship between internal model scores and policy performance. My work uses PyTorch, controlled simulator experiments, paired evaluation and explicit analysis of negative results. [Research overview](https://stelioszach.com/#world-models).

**Score-based MRI reconstruction — BSc thesis.** Reimplementation of a published reconstruction method, pretrained checkpoint conversion, uncertainty analysis and retrospective domain-shift experiments. The original architecture and pretrained prior are credited to their authors; this is not a clinical system. [Thesis and methods](https://stelioszach.com/#mri) · [Thesis PDF](https://stelioszach.com/documents/zacharioudakis-bsc-thesis-2026.pdf).

## Previous experience

**Former Head Engineer — Paphos Medical Association · June 2022–July 2026 · Pro bono.** I developed and donated AsklepiosMed to support the association's member services. My role ended in July 2026. The current platform, including subsequent development, is described separately in the case study. [Public platform](https://asklepiosmed.org/) · [Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md).

## Research code

| Project | What to inspect |
| --- | --- |
| [Speculative decoding lab](https://github.com/stelioszach03/colab-speculative-decoding-speed-lab) | Recorded inference experiments, baseline comparisons and workload-dependent results |
| [TrustQueryNet](https://github.com/stelioszach03/TrustQueryNet) | Noisy-label experiments, matched controls and external dataset evaluation |
| [Constraint-verification toolkit](https://github.com/stelioszach03/llm-smt-verifiable-reasoning) | Experimental candidate-generation pipelines beyond the bounded public verifier |

Repository READMEs distinguish prototypes, coursework and recorded experiments. Synthetic examples, small replay sets and recorded GPU runs are identified with their scope and limitations; they are not presented as production performance or peer-reviewed publications.

## Background and tools

**BSc in Computer Science**, National and Kapodistrian University of Athens — **June 2026**.

- **Research:** Python, PyTorch, NumPy, SciPy, model-based reinforcement learning, generative models and experimental evaluation.
- **Software:** FastAPI, Node.js/Express, React, PostgreSQL, Redis, Linux, Docker and automated testing.

I am interested in machine learning research and engineering opportunities where careful experiments and reliable implementation matter.
