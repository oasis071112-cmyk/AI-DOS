# Architecture

## Overview

AI-DOS is organized into modular knowledge domains.

Each module has a single responsibility and can evolve independently.

The system is designed to be reusable across different AI agents, coding assistants, and frontend frameworks.

---

## Architecture

```
AI-DOS
│
├── docs/
├── skill/
├── knowledge/
├── patterns/
├── components/
├── prompts/
├── examples/
├── review/
├── templates/
└── tokens/
```

---

## Module Responsibilities

### docs/

Project documentation.

Explains the vision, architecture, roadmap, and contribution guide.

---

### skill/

The AI entry point.

Defines how AI agents load and use the knowledge base.

---

### knowledge/

The core knowledge library.

Contains design philosophy, visual language, UX principles, motion, accessibility, engineering, and quality standards.

---

### patterns/

Reusable page patterns.

Examples include landing pages, dashboards, authentication flows, documentation sites, pricing pages, and enterprise websites.

---

### components/

Reusable component specifications.

Defines design rules instead of implementation details.

---

### prompts/

Task-specific prompts that leverage the knowledge base.

---

### examples/

Reference implementations and practical examples.

---

### review/

Quality assurance rules and self-review workflows.

---

### templates/

Reusable project templates.

---

### tokens/

Shared design tokens such as colors, spacing, typography, radius, shadows, and motion.

---

## Design Principle

Knowledge is independent.

Skills consume knowledge.

Patterns organize knowledge.

Components implement knowledge.

Review validates knowledge.

Everything starts from the knowledge base.
