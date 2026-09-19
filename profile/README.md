<div align="center">

<img src="https://raw.githubusercontent.com/citlyze/.github/main/assets/citlyze-icon.png" alt="Citlyze" width="88" height="88" />

# Citlyze

**See and grow how your brand shows up in AI search.**

[Website](https://www.citlyze.com) · [Docs](https://www.citlyze.com/docs) · [Free tools](https://www.citlyze.com/free-tools) · [Blog](https://www.citlyze.com/blog)

</div>

---

[Citlyze](https://www.citlyze.com) is an AI search visibility platform. It tracks how brands appear in answers from ChatGPT, Claude, Perplexity, Gemini, Google AI Overviews, and more: visibility scores per engine, tracked prompts, citations, competitor comparisons, optimization recommendations, and AI crawler analytics.

## Open source

| Repository | What it is |
| --- | --- |
| [citlyze-mcp](https://github.com/citlyze/citlyze-mcp) | MCP server access to your Citlyze workspace: hosted endpoint, Gemini CLI extension, and Claude Desktop extension |
| [citlyze-skills](https://github.com/citlyze/citlyze-skills) | Agent skills (open SKILL.md standard) for AI visibility reports, citation gap analysis, prompt audits, action plans, and a standalone AEO page audit |
| [ai-readable](https://github.com/citlyze/ai-readable) | CLI, GitHub Action and Agent Skill that show what each AI crawler actually gets from your pages and fail CI when a deploy makes a page unreadable to AI search |

Check a page from the terminal, no account needed:

```bash
npx ai-readable example.com/pricing --render
```

Quick start with any SKILL.md-compatible agent (Claude Code, Codex, Cursor, Gemini CLI, and more):

```bash
npx skills add Citlyze/citlyze-skills
npx skills add Citlyze/ai-readable
```

Or connect the read-only MCP server directly:

```text
https://app.citlyze.com/api/mcp
```

Setup guides for every client are in the [MCP docs](https://www.citlyze.com/docs/mcp/overview).

## Free tools

No account needed: [AEO grader](https://www.citlyze.com/free-tools/aeo-grader) · [llms.txt generator](https://www.citlyze.com/free-tools/llms-txt-generator) · [AI robots.txt generator](https://www.citlyze.com/free-tools/ai-robots-txt-generator) · [more](https://www.citlyze.com/free-tools)
