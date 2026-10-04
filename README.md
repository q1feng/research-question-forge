# Research Question Forge

English | [简体中文](README-zh.md)

> **Bringing the Focus Back to Research Itself.**

Good research starts with good questions. Research Question Forge is a composable research skill dedicated to turning observations and early ideas into consequential research questions and compelling research directions. Through dialogue, engagement with the literature, and iterative refinement, it helps clarify what to investigate, why it matters, and what is worth pursuing.

[Start without installation](en/question-forge-guide.md) · [Install the Skill](en/usage.md) · [中文使用](zh/usage.md)

## Why this exists

Research often begins before searching or writing: an unexpected observation, a practical difficulty, or an explanation that does not quite fit. The challenge is deciding whether it points to a knowledge problem, what existing work already answers, and where a feasible contribution might lie.

Forge supports that formative work. It provides better questions and frameworks to search, reading, design, and writing workflows rather than replacing those capabilities. It can be used across disciplines and research stages.

## How it works

```text
Observation → Early ideas → Question abstraction
                                    ↕
                            Literature feedback
                                    ↓
                         Expansion / decomposition
                                    ↓
                         Research foothold → Framework

New evidence / feedback ──→ Question abstraction
                        ├─→ Expansion / decomposition
                        └─→ Research framework
                        ╌╌→ Rethink observation, ideas,
                            and how questions are formed
```

Solid arrows show direct progress and revision: new evidence and feedback can reshape question abstraction, expansion or decomposition, and the research framework together. Dashed arrows show deeper epistemological reflection: why certain phenomena draw our attention, how we observe and interpret them, which assumptions shape our ideas, and how observations become questions. Both forms of feedback can recur throughout the work, before a framework or draft is complete.

Enter at the current stage. The assistant asks a few consequential questions, uses available evidence, and maintains the framework as understanding changes. The researcher chooses substantial changes of direction.

## Question Expansion and Question Decomposition

**Expansion** asks whether a local tension reveals a more general relationship, mechanism, or constraint. It connects observations to significance without assuming that broader means better.

**Decomposition** turns an oversized question into sub-questions and a research foothold that can be investigated with available time, materials, expertise, and evidence. Both movements remain open to revision.

## Literature as feedback

New literature should change understanding, not merely lengthen a reading list. It may reveal an existing answer, a closer baseline, a rival explanation, a narrower scope, or a more useful direction.

Forge records why a comparison matters, which conditions are comparable, what prior work covers, what a candidate approach might add, and what remains unverified. Baselines can be methods, theories, practices, or cases. Reported findings, inferences, expected capabilities, and reproduced results remain distinct.

## What makes a question worth asking?

Consider a real unknown, tension with existing knowledge, the value of a negative answer, appropriate scope, a defensible evidence route, and a feasible foothold.

Forge does not try to automate research taste. It makes the judgments behind it explicit, discussable, and revisable. It does not assign an automatic topic score or decide on the researcher's behalf.

## What it produces

Default: **research-framework.md**. Add **research-comparison.md** only when comparisons need a separate record.

| Readable research argument | Structured information |
|---|---|
| Observation, motivation, and current understanding | Objects, conditions, facts, and unknowns |
| Central question, sub-questions, and significance | Question boundaries and evidence for the gap |
| Closest work and competing explanations | Sources, roles, comparable conditions, and coverage |
| Candidate directions and research foothold | Approaches, possible contributions, and constraints |
| Evidence route and current decisions | Required checks, user choices, open issues, and next work |

The framework connects **question → prior work → candidate direction → evidence → decision**. It is a working research argument, not an automatically validated discovery or a finished paper.

## Composable by design

No specific search, reading, review, writing, or proposal workflow is required. Pass the framework to your preferred literature tools, domain Skills, design or analysis agents, or your own process. Handoffs state the question, evidence required, sources, limits, and decisions to preserve.

Retrieval and file access depend on the host. Without them, the assistant works from supplied material and marks unresolved checks; it does not invent searches or citations.

## Quick start

Attach the [portable guide](en/question-forge-guide.md) to a chat, or install the complete [English Skill folder](en/research-question-forge-en/SKILL.md) in your client's supported Skill directory. Keep its references. The Chinese Skill has a separate name and can coexist with it.

> Use $research-question-forge-en. I observed …; my current idea is …; I have these sources and resources …. Help me form the research question before choosing a final topic. Use new literature and feedback to revise the framework as we go.

The ellipses are input prompts, not a research case. You do not need to complete a long questionnaire. See [usage](en/usage.md) for installation and continuation.

## Research principles

- Distinguish practical goals, knowledge gaps, questions, approaches, and titles.
- Preserve counterevidence and the researcher's decisions; fit evidence to the discipline.
- Never invent novelty, reading depth, reproduction, resources, or results.
- Keep significance broad only where justified, and research scope manageable.
- Keep private research out of public contributions, even when anonymized.

## Project structure and participation

Each language directory contains usage instructions, a complete portable guide, and an independently installable Skill. SKILL.md routes to references; agents/openai.yaml provides client metadata. Build and validation scripts maintain same-language consistency without translating editions.

Contributions: [CONTRIBUTING.md](CONTRIBUTING.md). Changes: [CHANGELOG.md](CHANGELOG.md). Adaptation: [maintenance guide](maintenance-guide-en.md). Citation metadata: [CITATION.cff](CITATION.cff). Licensed under [MIT](LICENSE).
