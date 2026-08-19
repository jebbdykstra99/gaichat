# gaichat

Generative AI room. Best uses, policies, laws around the world, how to actually use the tools.

This is a **static** dress rehearsal of the bakasan.art SubX chrome (three-column X-like shell: left nav, center feed, right rail, hash routes, sign-in modal, mobile hamburger). It is **not** the FastAPI / Next `subx` stack. No React, no Next, no FastAPI, no Firebase, no model calls, no `fetch`.

Wordmark: **Generative AI**. Domain: gaichat.com. Tagline (locked): *Tools, not oracles.*

Dummy posts teach Grok, Cursor, Claude, Gemini, and ChatGPT as **tools with receipts** — verify, don't worship. Honest about drafts, code, search, and rubber-ducking. Honest about legal advice, live facts without checking, and secrets. EU AI Act / policy chatter appears as dummy cards, **not legal advice**.

**grokchat.com stays dark.** This is not that flagship. This is not X.com. No AskAI. No live model. No Jebb contact in the chrome.

## GitHub Pages + custom domain

These files are meant to drop into an empty public repo `jebbdykstra99/gaichat` and be served from GitHub Pages at **gaichat.com**.

1. Push this folder’s contents to branch `main` (site root, not `/docs`).
2. Repo **Settings → Pages**: Deploy from branch `main` / `/` (root).
3. Custom domain: `gaichat.com`. The `CNAME` file in this repo already contains exactly that.

**DNS at GoDaddy still needs to point at GitHub Pages.** Do not change DNS from this repo. Typical GitHub Pages records:

- Apex `A` records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- or a `CNAME` for `www` to `jebbdykstra99.github.io`

Until DNS is pointed, Pages will serve on `https://jebbdykstra99.github.io/gaichat/` only if the repo is project-pages configured; for the custom domain, use a user/org Pages root as above.

## What this is / is not

- Feed-first dummy posts about using generative tools well (Grok, Cursor, Claude, Gemini, ChatGPT, open weights vs hosted, work usage, EU AI Act chatter). Fake handles only.
- Ranking chrome (For You / Following / Hot / New) is UI only.
- Sign-in modal closes with X, Escape, or overlay click. Auth is stubbed locally. No live accounts.
- Right rail is dummy **In the lab** / **Policy desk** cards. Links stay on-site (`#explore`).
- No AskAI. No live OpenAI / xAI / Google URLs. No cross-post to X. We are not X.com.
- Footer: dummy feed, not legal advice, not a model.
- **grokchat stays dark.** Do not light that domain from this folder.
