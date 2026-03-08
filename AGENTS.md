# Vibe Coder Docs - Project Instructions

## Project Overview
A Mintlify documentation site providing engineering wisdom and best practices for vibe coders (non-engineers using AI coding tools like Claude Code, Codex, Antigravity, etc).

## Structure
- `/docs` — Mintlify docsite (MDX files + docs.json config)
- `/vibe-coder-docs-skills` — Skills for AI agents working with this repo
- `/skill-library` — General development skills shared across projects
- `/.claude` — Claude Code configuration

## Content Guidelines
- Target audience: non-engineers and early-stage developers using AI coding tools
- Tone: approachable but technically accurate — teach, don't gatekeep
- Every topic should explain *why* something matters, not just *what* to do
- Use real-world examples and common mistakes as teaching tools
- Content should be useful to both human readers and AI agents consuming the docs

## Mintlify
- Docs live in `/docs` with `docs.json` as the config
- Pages are `.mdx` files (MDX = Markdown + JSX components)
- Navigation structure is defined in `docs.json`
- Run locally with `npx mintlify dev` from the `/docs` directory

## Writing Docs
- Each MDX file needs frontmatter with `title`, `description`, and optionally `icon`
- Use Mintlify components: `<Card>`, `<CardGroup>`, `<Tip>`, `<Warning>`, `<Note>`, `<Accordion>`, `<AccordionGroup>`, `<Steps>`, `<Step>`
- Keep pages focused — one concept per page
- Link between related pages liberally
