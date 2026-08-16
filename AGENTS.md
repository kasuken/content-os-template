# Content OS operating instructions

This repository is a reusable content workspace. Treat files in `system/` and channel rules as the source of truth for voice and publishing decisions.

## Context order

1. `system/creator-profile.md`
2. `system/positioning.md`
3. `system/style-guide.md`
4. `system/writing.md`
5. `.agents/skills/writing/SKILL.md` for reader-facing prose
6. Relevant `channels/*/rules.md`
7. Relevant `pillars/*`
8. Relevant templates and workflows

## Default behavior

- Clarify the audience, channel, objective, and angle before drafting when they are missing.
- State assumptions and use placeholders instead of inventing facts, metrics, quotes, or experience.
- Preserve the configured voice; remove generic, unsupported AI language.
- Check for related material before creating a new draft.
- Keep personal data, credentials, confidential customer information, and unlicensed material out of the repository.
- Before working in a subdirectory, follow any closer `AGENTS.md` file.

## Quality gate

Before marking a draft ready, check factual claims, audience fit, channel requirements, voice, links, and calls to action.

## Commands and workflows

Load the matching file in `workflows/` before acting. The `.agents/skills/` adapters expose the same commands to compatible coding agents.

- `IDEA` — turn rough input into a structured idea; do not draft the final content.
- `BRAINSTORM` — clarify an idea, audience, channel, and angle.
- `BRIEF` — create an approved content brief before drafting.
- `WRITE` — create a channel-ready draft from a brief.
- `REVIEW` — assess a draft for voice, hook, clarity, specificity, and practical value.
- `REPURPOSE` — adapt approved source material for another channel while preserving the message.
- `ANALYZE` — extract evidence-based lessons from published content.
