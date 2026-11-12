# Agent architecture Resources

## Knowledge

- [Article: "Effective context engineering for AI agents" (Anthropic Engineering)](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Context as a finite attention budget, context rot, just-in-time retrieval, compaction, notes, sub-agents. Use for: what to keep in context, memory and retrieval design.
- [Docs: Context windows (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/context-windows)
  What counts toward the window, how turns accumulate, compaction and context editing. Use for: token accounting and cost reasoning.
- [Docs: Memory tool (Claude Platform)](https://platform.claude.com/docs/en/agents-and-tools/tool-use/memory-tool)
  Client-side file memory across sessions, handler commands, security notes. Use for: designing notes saved between sessions.
- [Article: "Contextual Retrieval" (Anthropic)](https://anthropic.com/research/contextual-retrieval)
  Chunking, embeddings plus BM25, reranking, with measured results. Use for: finding the right page in a long manual.
- [Article: "Effective harnesses for long-running agents" (Anthropic Engineering)](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)
  Progress notes across sessions as a case study. Use for: multi-session designs. (Linked from the docs; not yet read in full.)
- [Docs: Compaction (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/compaction)
  Server-side summarising of long conversations. Use for: sessions that outgrow the window. (Linked from the docs; not yet read in full.)

## Wisdom (Communities)

- [LangChain forum](https://forum.langchain.com/)
  Moderated product forum with retrieval and agent threads. Use for: practical questions on chunking and memory. Advice is framework-specific, so check it fits.

## Gaps

- No source yet on cost estimation for the team's specific model budget; needed for the mission's cost constraint.
