# Context Engineering Library

A repository of reusable prompts and best practices for building applications (ai optional LOL).

## Overview

Context engineering optimizes AI outputs through structured prompt frameworks, RAG strategies, and system-level instructions. Rather than complex compute-heavy approaches, this library uses simple referencing (@ref syntax in most IDEs) to compose prompts dynamically.

## Quick Start

1. Reference framework files in your prompts using `{design}`, `<design>`, or similar delimiters
2. Combine pre-prompts with referenced content: `Use {design} when creating {concept}. <design>@design_prompt_1</design>`
3. Pull repo into `/docs` and start referencing

## Prompt Categories

**Design**: Template-driven prompts for initial creation or element enhancement

**Build**: Technical scaffolding and project kickstarters aligned to designs

**Judge**: Critical evaluation prompts that challenge and iterate on existing work

## Rule Vectors

**Prompt/Context Engineering**: Instruction clarity, context frameworks, output formatting, chain-of-thought, few-shot templates

**Agent Rules**: Command completion, response modifiers, tone/style, error handling, memory usage

**RAG Optimization**: Embedding patterns, retrieval strategies, context window utilization, chunking standards, relevance weighting

**System Instructions**: Agent behavior, tool protocols, safety guardrails, multi-agent coordination, response moderation

**Language Rigidity**: Semantic frameworks, domain terminology, context-sensitive patterns, precision/generalization balance

**UX/UI Integration**: Command center design, mobile/desktop optimization, visual cue integration, error standardization

**Design Paradigms & Frameworks**: Command interfaces, button mechanics, conversational UI, direct manipulation, form patterns, modal schemas

## Implementation

- Embed in system prompts
- Integrate with RAG systems
- Implement in frontend interfaces
- Fine-tune with rule-aware training
- Enforce via middleware

## Contributing

Submit PRs with:
- Established format adherence
- Compliance/violation examples
- Expected outcomes
- Related rule cross-references

## Roadmap

**2026 Q1**: Design Frameworks, Framework Compatibility, Context/Agent Rules optimization

**2026 Q2**: UI/UX Integration

**2026 Q3**: Language Rigidity, RAG Optimization

**2026 Q4**: System Prompts

---

**Main changes**: Removed informal language, restructured for clarity, tightened descriptions, moved roadmap context into structured timeline, eliminated redundancy between sections.
