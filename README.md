# Academic Writing Skill

[中文](README_zh.md) | English

A process-based academic writing skill for thesis and research paper guidance, derived from the nine-unit framework of *Successful Writing: Student Book* (2nd ed., 2013, Zou Shen).

## Overview

This skill treats academic writing as a staged process rather than sentence-level polishing. It guides users from researchable question → evidence collection → proposal & outline → drafting → source integration → revision → evaluation.

## Features

- **Nine-stage workflow**: Topic selection → Preliminary research → Field research → Research proposal → Working outline → Drafting → Source integration → Revision & editing → Whole-paper evaluation
- **Three-layer diagnosis**: Research design → Argument & paper design → Language & presentation
- **Evidence discipline**: No fabricated sources, citations, data or findings; evidence gaps are explicitly identified
- **Literature review discipline**: Synthesis and evaluation, not mere listing
- **Diagnostic priority**: From global (research question, evidence, organization) to local (sentence clarity, grammar, formatting)

## File Structure

```
academic-writing/
├── SKILL.md                          # Main skill definition and task router
├── agents/
│   └── openai.yaml                   # Agent interface config
└── references/
    ├── book-framework.md             # Nine-unit framework from the source book
    ├── research-topic.md            # Topic selection and research questions
    ├── sources-and-literature.md     # Library research and literature review
    ├── field-research.md             # Observation, questionnaires, interviews
    ├── proposal-and-outline.md       # Research proposal and working outline
    ├── paper-sections.md             # Drafting and major paper sections
    ├── source-integration.md         # Quotation, paraphrase, citation, plagiarism prevention
    ├── revision-and-evaluation.md    # Revision, editing, whole-paper evaluation
    └── response-patterns.md          # Reusable response templates
```

## Usage

This skill is designed to be used with AI assistants that support custom skills. It activates when users ask for help with:

- Research topic selection and narrowing
- Literature review planning and synthesis
- Research proposal and outline design
- Paper section drafting (abstract, introduction, methods, results, discussion, conclusion)
- Translation/paraphrase and citation guidance
- Paper revision and whole-paper review

## Core Principles

1. Start from the user's actual task and available evidence
2. Separate research design, argument design, and language presentation layers
3. Do not fix weak papers only at the language level when the real problem is research design or organization
4. Do not invent sources, data, participants, methods, or results
5. Distinguish direct quotation, paraphrase, summary, interpretation, and the writer's own claim
6. Prefer diagnosis plus action: tell the user what is wrong, why it matters, and how to fix it

## Installation

Copy the entire `academic-writing/` folder into your skill directory. The exact path depends on your AI assistant platform.

## License

[MIT](LICENSE)
