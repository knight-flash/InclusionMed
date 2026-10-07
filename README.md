# InclusionMed

**Inclusive medical intelligence, grounded in real healthcare work.**

InclusionMed is a research initiative developing a framework for community-built evaluation of medical AI. We want to connect the needs of patients, professionals and healthcare services with tasks whose outcomes can be examined and reproduced.

[Why InclusionMed](#why-inclusionmed) · [Task map](#task-map) · [Evaluation](#how-evaluation-should-work) · [Contribute](#contribute)

## Call for contributors

Help us identify healthcare work that AI should be evaluated against. Bring a practical task, recommend an existing benchmark, or contribute medical, technical or local-context expertise. You do not need to write code to help define a useful task.

[See ways to contribute →](#contribute)

## Why InclusionMed?

Healthcare is more than answering medical questions. It includes finding care, making sense of information, planning treatment, coordinating services, following up, and supporting research and administration.

Those activities involve different people, languages and care settings. A useful evaluation should make clear **who a task represents, what work it measures, and what a successful outcome means**.

InclusionMed aims to organise that evidence so that strengths, limitations and gaps are easier to understand.

## Inclusion × Effectiveness

| Perspective | The question we ask |
| --- | --- |
| **Inclusion** | Whose needs, languages and care settings does the evaluation represent? |
| **Effectiveness** | How well does the system complete useful healthcare work? |

These are complementary perspectives for examining tasks and results. They are not a published formula for combining scores.

## Task map

We organise healthcare work along three dimensions. A task can involve more than one role or work area; its labels should describe the actual work being evaluated.

### People supported

| Role | Examples of work |
| --- | --- |
| Patients & families | Understanding care options, preparing questions and finding appropriate services |
| Healthcare professionals | Reviewing evidence, preparing records and supporting clinical workflows |
| Service & administrative staff | Coordinating care, scheduling services and handling administrative processes |

### Healthcare work areas

- Access to Care
- Clinical Assessment & Diagnosis
- Care Planning
- Care Delivery & Coordination
- Follow-up & Monitoring
- Research & Education
- Healthcare Administration

### Capability tags

**Medical Knowledge · Communication · Work Product Generation**

For example, a care-navigation task can serve patients and families in Access to Care, with Communication as a relevant capability. This is an example of classification, not a released benchmark or evaluation result.

## How evaluation should work

A proposed task should describe the healthcare need, available inputs, expected outputs, medical basis and criteria for judging a useful result.

Our proposed review principles are:

1. **Relevant:** measure work that addresses a real healthcare need.
2. **Credible:** ground references and scoring in medical or professional evidence and qualified human review.
3. **Available:** make materials usable under clear licences and access conditions.
4. **Reproducible:** document the task version, model, prompts, tools, configuration and scoring so another reviewer can check the result.
5. **Complementary:** explain the evidence the task adds and its overlap with existing evaluations.
6. **Attentive to representation gaps:** identify missing languages, populations, regions and resource settings.

Results should retain their original metrics, conditions and limitations. Missing results are not zero, and scores from different benchmarks should not be combined without an agreed method.

[Download the evaluation-record checklist](assets/inclusionmed-evaluation-checklist.md)

## What we are building

| Part | Purpose |
| --- | --- |
| **Index** | An overall view of model performance, with the evaluation evidence accessible alongside it |
| **Atlas** | A task-level view of benchmarks, coverage and results organised by healthcare work |
| **Methodology** | Principles for admission, classification, evaluation and reporting |
| **Community resources** | Templates and guidance for proposing tasks and reviewing evidence |

These parts belong to the wider InclusionMed project. This page provides an introduction and a starting point for participation.

## Contribute

There are three ways to help:

- **Bring a healthcare task.** Describe who needs help, the setting, the available inputs and what a useful outcome would look like.
- **Recommend a benchmark.** Share an existing evaluation, dataset or tool, together with its documentation, permissions and contribution to the task map.
- **Review the evidence.** Contribute medical knowledge, evaluation engineering, reproducibility checks, language expertise or local context.

The proposed process is **bring a task → share the essentials → review and reproduce → refine and release**.

Start with the [task / benchmark proposal template](assets/inclusionmed-task-proposal.md). Medical and technical collaborators can help develop the parts you cannot complete on your own.

Public submission is not open yet. Existing collaborators can share a prepared proposal with their InclusionMed project contact.

## Current stage

The framework, review process and participation materials are in development. The current website demonstrates an interactive Index and Atlas.

Index scores and the Atlas illustrative view use fictional data. The separate Atlas public-reference view preserves reported results and source links; those results are not InclusionMed evaluations or admission decisions.

Reviewed InclusionMed results, a final aggregation method, a verified public submission channel, and confirmed contributor credits remain to be established.

## Resources

- [Task / benchmark proposal template](assets/inclusionmed-task-proposal.md)
- [Evaluation-record checklist](assets/inclusionmed-evaluation-checklist.md)
- [中文内容审阅稿](README.zh-CN.md)

The content structure was informed by the [OpenRSI Index README](https://github.com/OpenRSI-Foundation/OpenRSI-Index/blob/main/README.md). InclusionMed's healthcare task map, evaluation principles and contribution materials come from the InclusionMed project.
