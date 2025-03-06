# Awesome MDC

![Awesome](https://awesome.re/badge.svg)

A curated list of high-quality **Multi-Document Context (MDC) rules**, a Markdown-based standard for providing structured, project-specific instructions to AI models in Retrieval-Augmented Generation (RAG) contexts. Originally developed for the Cursor IDE, MDC rules are poised to become a universal approach for enhancing AI-assisted workflows across diverse tools and platforms.

---

## Table of Contents

- [What are MDC Rules?](#what-are-mdc-rules)
- [Why Use MDC Rules?](#why-use-mdc-rules)
- [How to Contribute](#how-to-contribute)
- [Awesome MDC Rules](#awesome-mdc-rules)
  - [Cursor-Specific MDC Rules](#cursor-specific-mdc-rules)
  - [General RAG Context MDC Rules](#general-rag-context-mdc-rules)
- [Writing Effective MDC Rules](#writing-effective-mdc-rules)
- [License](#license)

---

## What are MDC Rules?

MDC rules are Markdown files (typically with a `.mdc` extension) that combine:

- **Frontmatter**: A YAML section at the top with metadata, such as a description and file patterns (globs) the rule applies to.
- **Body**: Markdown-formatted instructions, guidelines, or context that an AI can use to understand and interact with a codebase or dataset.

Born in the Cursor IDE’s `.cursor/rules` directory, MDC rules are now envisioned as a flexible, tool-agnostic standard for RAG contexts, where AI models retrieve and apply relevant information dynamically.

---

## Why Use MDC Rules?

- **Modularity**: Break instructions into small, reusable rules instead of relying on monolithic files.
- **Context Awareness**: Apply rules selectively based on file patterns or project areas, keeping AI responses focused.
- **Portability**: The Markdown format ensures compatibility with any AI tool supporting RAG.
- **Scalability**: Ideal for complex projects, enabling tailored instructions for different components.

---

## How to Contribute

Help grow MDC as a standard by contributing:

1. **Create or share MDC rules**: Develop rules that showcase best practices or solve real-world problems.
2. **Submit a pull request**: Include your `.mdc` file and a brief description of its purpose.
3. **Document your work**: Ensure clarity for others adopting your rules.

Contributions fuel this project’s mission to establish MDC as a universal RAG standard.

---

## Awesome MDC Rules

### Cursor-Specific MDC Rules

These repositories highlight MDC rules designed for the Cursor IDE:
