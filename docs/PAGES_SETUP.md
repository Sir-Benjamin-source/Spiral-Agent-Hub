# Enable GitHub Pages (required for Discord legal URLs)

1. Open https://github.com/Sir-Benjamin-source/Spiral-Agent-Hub/settings/pages  
2. Under **Build and deployment** → **Source**, choose **Deploy from a branch**.  
3. Branch: `main` · Folder: `/ (root)` · Save.  
4. Wait one to two minutes.  

Expected URLs:

- https://sir-benjamin-source.github.io/Spiral-Agent-Hub/
- https://sir-benjamin-source.github.io/Spiral-Agent-Hub/privacy
- https://sir-benjamin-source.github.io/Spiral-Agent-Hub/terms

If markdown links 404, add a `.nojekyll` file at repo root (empty) and re-check, or use the `privacy.md` / `terms.md` raw GitHub URLs as a temporary fallback (some portals accept them; Discord prefers proper https pages).

## Discord Developer Portal

1. Application → **Settings** / legal fields (or OAuth / bot listing fields as shown).  
2. Privacy Policy URL → Pages privacy URL above.  
3. Terms of Service URL → Pages terms URL above.  
4. Save. Continue bot token / intents / invite flow when the phone is charged.
