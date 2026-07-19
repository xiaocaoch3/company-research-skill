# Company Research Skill for Codex

An evidence-first Codex skill for structured company research, investment analysis, job-seeker due diligence, product and competitive analysis, and industry research.

## Core approach

```text
Research context
-> Research questions
-> Evidence collection
-> Fact organization
-> Analysis
-> Qualified conclusion
-> Counterevidence and falsification
```

The skill emphasizes:

- framework before conclusion;
- clear separation of facts, analysis, and conclusions;
- source quality and materiality;
- business model, industry position, upstream/downstream value chain, and value capture;
- evidence-based competitive advantage and growth analysis;
- business-specific financial and operating validation;
- balanced risk analysis without inventing negative points;
- role-specific output for investors, job seekers, product teams, entrepreneurs, and industry researchers.

In job-seeker mode, the output must include the company's official website and official careers site.

## Repository structure

```text
company-research-skill/
├── README.md
└── .codex/
    └── skills/
        └── company-research/
            ├── SKILL.md
            └── agents/
                └── openai.yaml
```

## Install

Copy the skill folder into your Codex skills directory:

```text
.codex/skills/company-research
```

For a personal installation, place `company-research` under your Codex home skills directory. For a project-scoped installation, keep the included `.codex/skills/company-research` structure in the project.

Restart or reopen Codex if the skill is not discovered immediately.

## Use

Invoke the skill explicitly:

```text
Use $company-research to analyze DJI from a job-seeker perspective.
```

```text
Use $company-research to evaluate Tencent from an investment perspective.
```

The skill can also trigger automatically for company research and due-diligence requests.

## Version

V1 — core research framework and role-adaptive workflow.
