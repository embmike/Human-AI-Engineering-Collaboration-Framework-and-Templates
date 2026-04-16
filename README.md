# Human-AI Engineering Collaboration Framework and Templates

A practical framework for structuring collaboration between humans and AI in engineering projects.

This repository helps teams use AI in a controlled, transparent, and high-quality way.  
Instead of relying on trial and error, it introduces a clear working model:

- the human defines the frame
- the AI works inside that frame
- quality gates make progress and uncertainty visible
- templates make the process reusable across projects

## Why this repository exists

AI can accelerate engineering work significantly.  
But without a clear project frame, defined responsibilities, and explicit review points, AI-supported work often becomes inconsistent, correction-heavy, and difficult to validate.

This repository was created to address exactly that problem.

It provides a reusable approach for Human-AI collaboration that supports:

- project framing
- architecture and workflow alignment
- bounded AI execution
- quality-gate-based progress
- reusable templates for repeatable engineering work

## What this framework provides

The repository combines two complementary parts:

### [Collaboration](./human_ai_collaboration_docs/collaboration/README.md)

Defines the Human-AI collaboration model.

It describes:

- roles and responsibilities
- project framing
- quality gates
- preparation rules before AI execution
- guidance for how humans and AI should work together during engineering projects

### [Templates](./human_ai_collaboration_docs/templates/README.md)

Provides the reusable operating kit for applying the framework in real projects.

It includes:

- checklists
- prompts
- work-package briefs
- test-case briefs
- JSON templates for project framing
- recovery and process-support documents

## Core idea

The central idea is simple:

> The human should define the frame.  
> The AI should execute inside that frame.  
> Both should use visible quality gates to manage uncertainty.

This makes AI-supported engineering more:

- structured
- reproducible
- reviewable
- scalable across projects

## Who this is for

This repository is intended for:

- engineers
- embedded developers
- software developers
- architects
- technical leads
- teams experimenting with AI-assisted development in a more disciplined way

It is especially useful when you want to move from ad-hoc prompting to a more explicit engineering process.

## Quick Start

1. Open the [Collaboration](./human_ai_collaboration_docs/collaboration/README.md) section to understand the process model.
2. Continue with the [Templates](./human_ai_collaboration_docs/templates/README.md) section to access the reusable artifacts.
3. Copy `human_ai_collaboration_docs/` into your project if you want to use the framework as a portable starter kit.
4. Begin with the preflight checklist and the first work-package brief.
5. Run the process gate by gate.

## Repository Structure

```text
human_ai_collaboration_docs/
├── collaboration/
│   └── README.md
└── templates/
    └── README.md
```

## License

This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
