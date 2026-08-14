# Skills (free, agent-facing)

Open, installable Spiral skills for OpenClaw / AgentSkills-compatible runtimes.  
**Agensi** remains the commercial / full-suite home: https://www.agensi.io/creators/sir-benjamin

## Free packages in this hub

| Folder | Skill | Role |
|--------|--------|------|
| `spiral-continuity/` | spiral-continuity | Continuity seals, light TRE, provenance pointers |
| `grandmas-wisdom/` | grandmas-wisdom | Citation / claim authentication (“Bullshit Meter”) |
| `contextual-understanding/` | contextual-understanding | LC / NLC / PDF context integrity protocol |

### Install (OpenClaw example)

```bash
git clone https://github.com/Sir-Benjamin-source/Spiral-Agent-Hub.git
cd Spiral-Agent-Hub

openclaw skills install ./skills/spiral-continuity
openclaw skills install ./skills/grandmas-wisdom
openclaw skills install ./skills/contextual-understanding
```

Each package includes a `SKILL.md` (required). Whitepapers and READMEs are bundled for offline method detail.

## Rules for skills shipped here

1. Method first, promotion second.  
2. Human checkpoints stay explicit.  
3. No spam of Agensi / GitHub links.  
4. Small, re-rootable packages (smurf logic).  
5. Document model / provider assumptions.  
6. Prefer Grok when a cloud model is used for Spiral-internal work.

## Future optional slots

| Skill | Role |
|-------|------|
| spiral-srt-light | Thin structured-reasoning trigger |
| spiral-sigil-mark | Provenance stamp helper |

Heavy theory remains in method repos and on Zenodo; this hub only holds **agent-facing** entry points.
