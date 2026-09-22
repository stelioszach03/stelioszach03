# Stelios Zacharioudakis

Machine learning research and software engineering, with a focus on world models, generative reconstruction and reliable evaluation.

[Portfolio](https://stelioszach.com/) · [CV](https://stelioszach.com/Stelios_Zacharioudakis_CV.pdf) · [Contact](mailto:stelios@stelioszach.com)

## Live demos

Open a working interface, then inspect the exact deployed adapter. Use the supplied synthetic examples; do not enter personal or confidential data.

| Open the demo | What it demonstrates | Deployed source |
| --- | --- | --- |
| **[Constraint verifier](https://stelioszach.com/demos/smt-verify/)** | Z3 checks a structured answer; no paid language-model call | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/smt-verify) |
| **[Text de-identification](https://stelioszach.com/demos/deid/)** | English entity detection and explicit transformations; review is required | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/deid) |
| **[Transaction graph explorer](https://stelioszach.com/demos/fraud-graph/)** | Graph features and scoring on synthetic, rule-labelled transactions | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/fraud-graph) |
| **[NYC subway monitor](https://stelioszach.com/demos/mta-scan/)** | Live public observations and a separate limited replay evaluation | [Adapter and UI](https://github.com/stelioszach03/stelioszach-portfolio/tree/main/demo-services/mta-scan) |

**Association platform:** [AsklepiosMed — public website](https://asklepiosmed.org/) · [Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md). Developed and donated as Head Engineer of the Paphos Medical Association, pro bono. Application source and member records remain private.

## Current work

**World-model learning and evaluation — ongoing, unpublished research.** I investigate imagination horizons, critic stability and the relationship between internal model scores and policy performance. My work uses PyTorch, controlled simulator experiments, paired evaluation and explicit analysis of negative results. [Research overview](https://stelioszach.com/#world-models).

**Score-based MRI reconstruction — BSc thesis.** Reimplementation of a published reconstruction method, pretrained checkpoint conversion, uncertainty analysis and retrospective domain-shift experiments. The original architecture and pretrained prior are credited to their authors; this is not a clinical system. [Thesis and methods](https://stelioszach.com/#mri) · [Thesis PDF](https://stelioszach.com/documents/zacharioudakis-bsc-thesis-2026.pdf).

**AsklepiosMed — Head Engineer, Paphos Medical Association, pro bono.** I developed and donated the association's member-services platform, covering onboarding, publishing, events, digital credentials and confidential casework. The engineering work includes access controls, operational monitoring, encrypted backups and restoration checks. [Public platform](https://asklepiosmed.org/) · [Engineering case study](https://github.com/stelioszach03/stelioszach-portfolio/blob/main/case-studies/asklepiosmed.md).

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
