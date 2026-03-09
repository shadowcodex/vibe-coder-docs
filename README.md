# Vibe Coder Docs

Engineering wisdom and best practices for vibe coders.

With the rise of AI-powered coding tools like Claude Code, Codex, and Antigravity, more people than ever are building software — many without traditional engineering backgrounds. This documentation site bridges the gap between "it works" and "it works well, securely, and reliably."

This is all built in public live, see it on commits and PRs as things are built.

## What's Inside

- **General IT** — Foundational knowledge every builder needs
- **Security** — Infrastructure, application, AI, and localhost security
- **General Programming** — Core programming concepts and patterns
- **Data Theory** — Understanding how data works
- **Databases & Storage** — Choosing and using data persistence
- **Building AI Applications** — Best practices for AI-powered apps

## Current Priorities in order

1. Define Topics and Concepts Areas
1. Build pipeline for content creation and deployment
1. Focus on security and patterns first
1. Build industry research and report pipeline
1. Grow other topics afterwards
1. Finally visit guides and docs on using vibe coding tools better (Tips & Tricks of sorts)
1. Whatever else comes next

## CURRENT TODO

- [ ] Pipeline builder. Topics + Descriptions + Opinions
- [ ] Pipeline Executor. Takes topics + Context => Delegates to Agent team to finalize => Pushes to human in the loop queue for approval/modify.
- [ ] Agent Team. Defined Agent teams for specific areas and topic concepts, orchestrated by claude code.
- [ ] Agentic Pipeline - Industry Research. Find most recent industry information regarding AI/LLM/Agentic. Source into report for self discovery and learning. Publish report 
- [ ] Agentic Pipeline - Industry Fails. Find most recent CVE's, Breaches, Ooops, Etc and make sure there are topics that cover them. If not flag them for potential pipeline inclusion.

## Project Structure

```
/docs                      — Mintlify documentation site
/vibe-coder-docs-skills    — AI agent skills for this repo
/skill-library             — Shared development skills
/.claude                   — Claude Code configuration
```

## Development

### Running Locally

```bash
cd docs
npx mintlify dev
```

## License

See [LICENSE](LICENSE) for details.
