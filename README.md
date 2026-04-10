# Explore Agent

[![Stars](https://img.shields.io/github/stars/Eita19/explore-agent?style=flat)](https://github.com/Eita19/explore-agent)
[![Based on](https://img.shields.io/badge/based-Claude%20Code-7B68EE?style=flat)](https://github.com/anthropics/skills)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> **Systematic code exploration for AI agents** — based on Claude Code's exploreAgent

**Trace paths, understand structure, find connections.**

---

## What is Explore Agent?

When you need to understand a codebase, you don't read every file. You map, trace, and connect.

Explore Agent teaches your AI agent a systematic approach:

- **Breadth First** — Overview first, then deep-dive
- **Depth First** — Follow one path completely
- **Pattern Based** — Find all occurrences efficiently

---

## When to Use

- "Explore the codebase"
- "How does X work?"
- "Find all files related to Y"
- "Understand the architecture"
- "Map the project structure"

---

## Workflow

### Step 1: Orient
```
What is the project?
What language/framework?
What is the main entry point?
```

### Step 2: Map
```
Directory structure
Key files
Dependencies
```

### Step 3: Trace
```
Follow imports/exports
Trace function calls
Find call sites
```

### Step 4: Connect
```
How do modules interact?
What are the data flows?
Where are the boundaries?
```

---

## Output Format

```markdown
## Exploration: [Topic]

### Overview
### Structure
### Key Findings
### Connections
```

---

## Quick Start

```bash
clawhub install explore-agent
```

---

*Based on [Claude Code exploreAgent](https://github.com/anthropics/skills)*
