# Discord application checklist

Use this when registering or finishing a Spiral / OpenClaw Discord bot.

## Legal URLs (required by Discord)

After GitHub Pages is enabled on this repo:

- **Privacy Policy:** https://sir-benjamin-source.github.io/Spiral-Agent-Hub/privacy  
- **Terms of Service:** https://sir-benjamin-source.github.io/Spiral-Agent-Hub/terms  

Enable Pages: repo **Settings → Pages → Deploy from a branch → `main` / root**.  
Details: [docs/PAGES_SETUP.md](../docs/PAGES_SETUP.md)

## Portal steps

1. [Discord Developer Portal](https://discord.com/developers/applications) → New Application (or open existing).
2. Paste Privacy + Terms URLs into the application’s legal / policy fields.
3. **Bot** tab → Add Bot → copy token (store offline; never commit).
4. Enable only the **intents** you need (start minimal; add Message Content only if required).
5. OAuth2 → URL Generator → scopes: `bot` (+ `applications.commands` if using slash commands).
6. Select bot permissions carefully (Send Messages, Read Message History, etc. — least privilege).
7. Invite the bot to your server with the generated URL.
8. Point OpenClaw (or your gateway) at the bot token via the Discord channel config — do not paste tokens into this repo.

## Operator notes

- Prefer **xAI / Grok** as the model provider for Spiral-internal agents.
- Keep the OpenClaw workspace lean; install skills from `skills/` rather than cloning the full lattice.
- Money / license verification in the Discord flow is separate from this repo; complete that on the phone when charged.
