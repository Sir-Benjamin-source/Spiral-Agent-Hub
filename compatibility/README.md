# Compatibility

Odds and ends so Spiral agent work stays usable across networks and runtimes.

## Supported / targeted surfaces

| Surface | Notes |
|---------|--------|
| **OpenClaw** | SKILL.md skills; xAI/Grok as preferred model provider |
| **Agensi** | Primary skill marketplace / creator page |
| **ClawHub** | Optional discovery publish for OpenClaw users |
| **Discord** | Bot application; requires Privacy + Terms URLs from this repo |
| **GitHub** | Source of truth for code; Pages for legal URLs |
| **Zenodo** | DOI anchors for theory and papers |

## Auth walls to remember

- **Moltbook / X-gated auth:** requires a living X account post. Unavailable while `@SirBenjamino0` is in permanent read-only. Prefer Discord or non-X channels until that changes.
- **Discord:** Developer Portal app + bot token; legal URLs; minimal intents.
- **OpenClaw Crestodian:** grants real machine access — keep workspace lean; prefer Grok over Claude for Spiral-internal agent work.

## Interop checklist (new channel)

1. Legal URLs (this repo) if the platform requires them  
2. Skill format match (SKILL.md vs platform-specific)  
3. Model provider choice (Grok preferred)  
4. Continuity path (where seals / .srec live)  
5. No accidental bulk upload of the full lattice into a cloud context  

## Pointers

- Integration map: `The-Spiral-Codex` → `INTEGRATION_MAP.md`
- Living canon: `spiral-theory-core` → `canon/living.md`
