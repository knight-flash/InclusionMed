# Contributing to InclusionMed

[Project overview](README.md) · [Website](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/) · [中文](CONTRIBUTING.zh-CN.md)

Help evaluate AI against real healthcare work. You can bring a task, recommend a benchmark or contribute expertise. You do not need a complete dataset or implementation to start a conversation.

## 1. Choose a way to contribute

| Contribution | A useful starting point |
| --- | --- |
| **Healthcare task** | Who needs help, the care setting, the work to be completed and what a useful outcome means |
| **Existing benchmark** | Source links, task description, evaluation method, licences and the evidence it adds |
| **Review or expertise** | Medical review, local context, language coverage, evaluation engineering or independent reproduction |
| **Documentation** | A concrete correction or suggestion for the overview, contribution guide or templates |

## 2. Prepare a proposal

Copy the [task / benchmark proposal template](assets/inclusionmed-task-proposal.md). Begin with the healthcare need and expected outcome; mark unknowns for review. Medical and technical collaborators can help develop the remaining parts.

The template asks for:

1. Contributor, proposal title and proposed owner.
2. Real healthcare need, inputs, outputs and scope.
3. People supported, healthcare work area, capability tags and representation.
4. Medical or professional basis, qualified reviewers and critical errors.
5. Materials, licences, permissions and access conditions.
6. Reproduction package, setup, model configuration, scoring and reviewable outputs.
7. Added value, related evaluations and overlap.
8. Review, release and contributor records.

Do not include identifiable patient information, credentials or restricted source data in issues, pull requests or attachments. Describe controlled access conditions and use approved sharing arrangements for protected materials.

## 3. Share the idea or proposed change

### Task ideas and benchmark recommendations

Open a [repository issue](https://github.com/knight-flash/InclusionMed/issues/new) with a short title and a summary of the need, expected output, proposed evaluation and relevant public sources. Link or paste the parts of the proposal that can be shared publicly. If the task is still an idea, say what remains to be decided.

Issues are a starting point for discussion and documentation feedback. A complete task-admission service and evaluation pipeline are still in development; no automated acceptance or response-time guarantee is currently provided.

### Documentation and public proposal materials

For a concrete file change, fork the repository, create a branch and open a pull request against this repository's default branch. Keep the change focused and describe what changed and why.

For a public task proposal, a suggested directory layout is:

```text
proposals/<short-task-name>/
  README.md          # Your completed proposal
  references.md      # Public sources and use conditions, if helpful
```

Create a proposal directory only for the material you are contributing. This suggested layout does not imply that task data, evaluation code or accepted tasks already exist here.

For documentation-only changes, check the relative links, images and Markdown preview. If a change affects both languages, update the English and Chinese documents together or identify the translation still needed.

## 4. Review and reproduce

The proposed process is **bring a task → share the essentials → review and reproduce → refine and release**.

Review should consider:

| Principle | What should be clear |
| --- | --- |
| **Relevant** | The healthcare need, intended user, actual work and useful outcome |
| **Credible** | Medical or professional references, qualified human review, scoring criteria and critical errors |
| **Available** | Usable materials, clear licences and access or redistribution conditions |
| **Reproducible** | Versioned tasks, setup, prompts, tools, model configuration, scoring and reviewable outputs |
| **Complementary** | The additional evidence the task contributes and its overlap with existing evaluations |
| **Representation gaps** | Missing languages, regions, populations or resource settings, and relevant local input |

LLM-generated annotations must not serve as reference answers or scoring criteria. Any AI assistance in preparing materials should be described along with the human review performed.

Use the [evaluation-record checklist](assets/inclusionmed-evaluation-checklist.md) to document an evaluation. Retain original metrics and conditions; missing results are not zero. Record controlled-data access so an authorised independent reviewer can reproduce the work.

## 5. Refine, document and credit

Address review findings, explain limitations and keep the proposal status explicit. Record contributors and their roles, the materials and code versions, and the maintenance plan before a release.

Sharing a proposal or opening a pull request does not imply benchmark admission, publication or authorship. Final review, release and credit arrangements remain to be established with the project team.

## Useful links

- [Project overview](README.md)
- [Task / benchmark proposal template](assets/inclusionmed-task-proposal.md)
- [Evaluation-record checklist](assets/inclusionmed-evaluation-checklist.md)
- [Website methodology](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/methodology)
- [Website contribution page](https://testmiodemo.renderoffice-pre.antgroup-inc.cn/contribute)
- [Repository issues](https://github.com/knight-flash/InclusionMed/issues)
