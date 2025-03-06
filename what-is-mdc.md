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
