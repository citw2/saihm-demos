# SAIHM demos

The landing page and runnable demos for **[SAIHM](https://saihm.coti.global)** — non-custodial, post-quantum memory for AI agents. One client-side-encrypted memory that every model can read, with erasure you can prove.

**Live page:** https://citw2.github.io/saihm-demos/

## Demos

One repo per model — each runs fully offline against an included blind sandbox (no account needed to try it), or live against the hosted endpoint with one environment variable:

- **[demo-claude](https://github.com/citw2/demo-claude)** · **[demo-openai](https://github.com/citw2/demo-openai)** · **[demo-deepseek](https://github.com/citw2/demo-deepseek)** · **[demo-qwen](https://github.com/citw2/demo-qwen)** · **[demo-kimi](https://github.com/citw2/demo-kimi)** · **[demo-glm](https://github.com/citw2/demo-glm)**

And three that show the whole point — one memory, many surfaces:

- **[demo-cross-model-memory](https://github.com/citw2/demo-cross-model-memory)** — one encrypted memory shared across **Claude, DeepSeek, Qwen, Kimi, GLM, GPT**, plus provable crypto-shred erasure.
- **[demo-claude-code](https://github.com/citw2/demo-claude-code)** — SAIHM as an MCP server for Claude Code, Cursor, and any MCP host.
- **[saihm-langchain](https://github.com/citw2/saihm-langchain)** — SAIHM as a LangChain `BaseChatMessageHistory` and a LlamaIndex `BaseMemory` for Python; the same store opens from both.

## Built on

- [@saihm/mcp-server-pro](https://github.com/SAIHM-Admin/saihm-mcp-server-pro) — the production sealing client ([npm](https://www.npmjs.com/package/@saihm/mcp-server-pro)).
- [@saihm/client-pro](https://github.com/SAIHM-Admin/saihm-client-pro) — post-quantum client crypto ([npm](https://www.npmjs.com/package/@saihm/client-pro)).
- [@saihm/mcp-server](https://github.com/SAIHM-Admin/saihm-mcp) — the open MCP thin-client ([npm](https://www.npmjs.com/package/@saihm/mcp-server)).

## Learn more

- [Token benchmark](https://github.com/citw2/saihm-token-benchmark) — recalling a bounded memory instead of resending the transcript cuts context tokens **62.8%–85.9%** across a multi-session task (offline, reproducible).
- [AI memory needs a standard](https://saihm.coti.global/blog/2026-05-18-ai-memory-needs-a-standard)
- [What makes SAIHM different](https://saihm.coti.global/blog/2026-05-31-what-makes-saihm-different)

**Join the protocol:** https://saihm.coti.global/join

Apache-2.0 © SAIHM
