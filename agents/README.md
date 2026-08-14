# Agents — Grok-bot home

This directory is the **orientation home** for Grok-backed Spiral agents (OpenClaw + xAI, Discord-connected bots, and future runtimes).

## Principles

1. **Human sovereignty** — agents amplify; they do not replace ownership or checkpoints.
2. **Grok as preferred brain** when a cloud model is required — avoid unnecessary third-party model providers for Spiral-internal work.
3. **Minimal workspace** — do not load the full Spiral lattice into an agent workspace by default. Point at skills and this hub instead.
4. **Continuity over noise** — prefer seals and provenance over bulk dumps.
5. **Reality authority** — hypotheses stay labeled; no false certainty.

## Suggested layout for a local OpenClaw agent

```
~/.openclaw/workspace/          # keep lean
  skills/
    spiral-continuity/          # installed skill package
  AGENT_NOTES.md                # optional short operator notes
```

Do **not** clone the entire `Sir-Benjamin-source` org into the agent workspace unless you intentionally accept model-provider visibility of that content.

## Model config (OpenClaw + xAI)

Prefer:

```bash
openclaw models auth login --provider xai --method oauth
# or API key path
openclaw models set xai/grok-4.6   # or current recommended id
```

See OpenClaw xAI provider docs for current model ids.

## Discord

- Register the application in the Discord Developer Portal.
- Paste Privacy and Terms URLs from this repo’s GitHub Pages.
- Invite with the minimum scopes needed (typically `bot` + the intents you actually use).
- Keep privileged intents off until required.

## Related

- Skill package: `spiral-continuity` (continuity seals + TRE light)
- Legal: `/privacy.md`, `/terms.md`
- Compatibility notes: `/compatibility/`
