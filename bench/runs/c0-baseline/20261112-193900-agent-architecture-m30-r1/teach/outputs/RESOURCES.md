# Agent architecture Resources

## Knowledge

- [Article: "Effective context engineering for AI agents" (Anthropic)](https://www.anthropic.com/research/effective-context-engineering-for-ai-agents?embedable=true)
  Context as a finite budget, context rot, compaction, note-taking, just-in-time retrieval. Use for: deciding what stays in context.
- [Docs: Context windows (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/context-windows)
  How the window works and how to manage it. Use for: current window sizes and limits.
- [Docs: Memory tool (Claude Platform)](https://platform.claude.com/docs/agents-and-tools/tool-use/memory-tool)
  File-based memory across conversations, run by your own code. Use for: designing session-to-session memory.
- [Article: "Context management" (Anthropic)](https://www.anthropic.com/news/context-management)
  Clearing old tool results plus memory. Use for: long-running agents.
- [Article: "Introducing Contextual Retrieval" (Anthropic)](https://www.anthropic.com/engineering/contextual-retrieval?utm_source=tldrai)
  Chunking, keyword plus embedding search, reranking, and the skip-RAG-under-200k-tokens note. Use for: finding the right manual page.

## Wisdom (Communities)

- Local: senior design reviewers and course instructor.
  Use for: critique of where each fact lives in the assistant.

## Gaps

- Not yet read in full: the sources above were read through search excerpts; open them before the design review. No source on per-token pricing yet.
