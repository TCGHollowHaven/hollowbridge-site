# Hollow Bridge Site

Official website and landing page for Hollow Bridge, a creator-focused live stream automation app.

Hollow Bridge currently focuses on Twitch and TikTok live stream workflows, with support for additional live streaming platforms planned for the future.

## Pages

```text
public/index.html
public/about.html
public/account.html
```

The Account page is the Stage 2 website foundation for Patreon subscription access. It links to the Hollow Bridge Patreon page and prepares the UI for the future Cloudflare Worker verification backend.

## Cloudflare Workers / Pages deploy settings

Project name:

```text
hollowbridge-site
```

Deploy command:

```bash
npx wrangler deploy
```

Path:

```text
/
```

This repo uses `wrangler.toml` with static assets served from the `public` folder.
