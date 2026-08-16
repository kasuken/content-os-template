# Content OS Template

A privacy-first workspace for planning, creating, reviewing, and publishing content. It contains no personal profile, content, audience data, or credentials.

## Initialize your Content OS

1. Click **Use this template** on GitHub and create a private repository for your work.
2. Clone your new repository and replace every `[TODO: ...]` placeholder, beginning with the files in `system/`.
3. Add your topic pillars in `pillars/`, channel rules in `channels/*/rules.md`, and reusable formats in `templates/`.
4. Store ideas and drafts in the matching channel folder. Move only reviewed work to `published/`.
5. Keep passwords, API keys, private customer data, and unredacted source material out of this repository.

## Structure

- `system/` — creator context, positioning, voice, and writing rules.
- `pillars/` — durable themes you publish about.
- `channels/` — channel-specific rules and content stages.
- `templates/` — reusable content formats.
- `workflows/` — repeatable creation and review processes.
- `courses/`, `ebooks/`, `samples/` — larger content products and supporting examples.
- `feedback/` — sanitized audience insights and lessons learned.

## Placeholder convention

Use `[TODO: ...]` for missing context, e.g. `[TODO: define target audience]`. Delete unused folders; the structure is meant to adapt to your workflow.

## Working with AI

Read [AGENTS.md](AGENTS.md) before asking an AI assistant to create or revise content. It explains the intended context order and quality checks.
