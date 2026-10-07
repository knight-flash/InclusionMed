<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/figures/InclusionMed-confluence-reverse.png">
    <img src="assets/figures/InclusionMed-confluence.png" alt="InclusionMed" width="567">
  </picture>
</p>

<p align="center">
  <strong>Inclusive medical intelligence, grounded in real healthcare work.</strong>
</p>

<p align="center">
  <a href="https://testmiodemo.renderoffice-pre.antgroup-inc.cn/"><img src="assets/figures/website-badge.svg" alt="Website — preview" height="30"></a>&nbsp;
  <a href="CONTRIBUTING.md"><img src="assets/figures/contributing-badge.svg" alt="Contributing guide" height="30"></a>
</p>

<p align="center">
  English · <a href="README.zh-CN.md">中文</a>
</p>

**InclusionMed** is a research initiative developing community-built evaluation of medical AI. We connect the needs of patients, healthcare professionals and services with tasks whose outcomes can be examined and reproduced.

Explore the interactive project on our **[website](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/)**. This repository brings together the project overview, contribution guide, proposal template and evaluation-record checklist.

## 📣 Call for contributors

Help us identify healthcare work that AI should be evaluated against. Bring a practical task, recommend an existing benchmark, or contribute medical, engineering, language or local-context expertise. **You do not need to write code to propose a useful task.**

Read **[CONTRIBUTING.md](CONTRIBUTING.md)** for the participation process, proposal requirements and review principles. Start with the [task / benchmark proposal template](assets/inclusionmed-task-proposal.md); use [repository issues](https://github.com/knight-flash/InclusionMed/issues) to discuss an idea or suggest an improvement.

## Why InclusionMed?

Healthcare is more than answering medical questions. It includes finding care, understanding information, planning treatment, coordinating services, following up, and supporting research and administration. Those activities involve different people, languages and care settings.

A useful evaluation should make clear **who a task represents, what work it measures, and what a successful outcome means**. InclusionMed aims to organise that evidence so that strengths, limitations and gaps are easier to understand.

| Perspective | The question we ask |
| --- | --- |
| **Inclusion** | Whose needs, languages and care settings does the evaluation represent? |
| **Effectiveness** | How well does the system complete useful healthcare work? |

These are complementary perspectives for examining tasks and results, rather than a published formula for combining scores. Read more in our [Mission](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/mission).

### Healthcare task map

We describe each task through **people supported × healthcare work area × capability**. A task can involve more than one role or work area; the labels should describe the actual work being evaluated.

| Dimension | Categories |
| --- | --- |
| **People supported** | Patients & Families; Healthcare Professionals; Service & Administrative Staff |
| **Healthcare work areas** | Access to Care; Clinical Assessment & Diagnosis; Care Planning; Care Delivery & Coordination; Follow-up & Monitoring; Research & Education; Healthcare Administration |
| **Capability tags** | Medical Knowledge; Communication; Work Product Generation |

<details>
<summary><strong>View the seven healthcare work areas</strong></summary>

| Work area | What it covers |
| --- | --- |
| Access to Care | Navigation, booking, referrals and financial or service-access barriers |
| Clinical Assessment & Diagnosis | Symptoms and history, tests, risk assessment and diagnosis |
| Care Planning | Treatment, prevention and health-management options and plans |
| Care Delivery & Coordination | Clinical records, handovers, carrying out a plan and coordinating care |
| Follow-up & Monitoring | Changes, treatment response, safety, adherence and continued support |
| Research & Education | Study design, evidence synthesis, analysis, research outputs and teaching |
| Healthcare Administration | Insurance, authorisations, payment, scheduling, resources and organisational quality |

</details>

For example, care navigation can serve patients and families in Access to Care, with Communication as a relevant capability. This illustrates classification; it is not a released benchmark.

### Research directions

The website outlines the following work in progress. These are research directions, not a catalogue of released, runnable benchmarks.

| Direction | Focus | Current stage |
| --- | --- | --- |
| Clinical Live Knowledge Bench | Medical knowledge as evidence changes | Planned |
| Single-response health conversations | Communication in a single response | In development |
| Multi-Turn Bench | Communication across a conversation | Proposed direction |
| EHR Agentic Bench | Work within electronic health record workflows | In development |
| RSI AutoResearch Bench | Research work and its outputs | In development |

### How evaluation should work

Tasks should be **relevant, credible, available, reproducible and complementary**, while addressing **representation gaps**. Medical references and scoring criteria require qualified human review. LLM-generated annotations must not serve as the reference standard.

Each evaluation should record the task and data version, model and setup, run conditions, scoring and review, results and uncertainty, and reproduction and credit. See the [evaluation-record checklist](assets/inclusionmed-evaluation-checklist.md) and website [Methodology](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/methodology).

Results should retain their original metrics, conditions and limitations. Missing results are not zero; combining different benchmarks requires an agreed method.

## Explore InclusionMed

| Website page | What you can find |
| --- | --- |
| [Mission](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/mission) | Why we evaluate medical intelligence through inclusion and effectiveness |
| [Index](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/observatory) | An overall view of model performance and comparisons |
| [Atlas](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/atlas) | Benchmarks, coverage and results organised by healthcare work |
| [Methodology](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/methodology) | Proposed admission, classification, evaluation and reporting principles |
| [Contribute](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/contribute) | Ways to bring healthcare tasks, benchmarks and expertise |
| [Resources](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/resources) | Project materials and reference resources |
| [About](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/about) | Project purpose, research context and current stage |

## Project status

The linked website is a **preview**. The framework, review process and participation materials are in development.

Index scores and the Atlas illustrative view use fictional data. The separate Atlas public-reference view preserves reported results and source links; these are not InclusionMed evaluations or admission decisions. Reviewed InclusionMed results, a final aggregation method and confirmed contributor credits remain to be established.

Repository issues provide a place for ideas and documentation feedback. The full benchmark admission and release process is still being developed; sharing a proposal does not imply acceptance.

## 🤝 Taking part

We welcome collaborators with **medical expertise**, **evaluation and engineering experience**, and **language or local-context knowledge**. These perspectives help define meaningful tasks, review evidence and make evaluations reproducible.

**[Read the contribution guide →](CONTRIBUTING.md)**

## Resources

- [Contribution guide](CONTRIBUTING.md)
- [Task / benchmark proposal template](assets/inclusionmed-task-proposal.md)
- [Evaluation-record checklist](assets/inclusionmed-evaluation-checklist.md)
- [Chinese overview](README.zh-CN.md)
- [License](LICENSE)

The README presentation is inspired by [OpenRSI Index](https://github.com/OpenRSI-Foundation/OpenRSI-Index). InclusionMed's healthcare task map, proposed evaluation principles and participation materials come from the InclusionMed project.
