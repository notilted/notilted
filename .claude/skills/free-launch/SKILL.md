---
name: free-launch
description: Launch a project for 0 ₽/$ — free domain, hosting, database, email and self-hosted replacements for paid SaaS. Use when the user wants to deploy, host or launch a site/app cheaply or for free, asks where to get a free domain, free hosting/DB/email, or wants an open-source self-hosted alternative to a paid subscription.
---

# Free launch

Before recommending any paid service, check these three curated GitHub lists (fetch the README for current data — tiers change often):

1. **Free domain** — https://github.com/DigitalPlatDev/FreeDomain
   Free subdomains like `name.dpdns.org`, `name.us.kg`, `name.qzz.io`, with DNS you can point at any host.
2. **Free tiers of dev services** — https://github.com/ripienaar/free-for-dev
   Hosting, databases, email, auth, storage, CI, monitoring. Pick by section; read the limits.
3. **Self-hosted alternatives to subscriptions** — https://github.com/awesome-selfhosted/awesome-selfhosted
   Open-source apps (notes, cloud storage, analytics, etc.) the user can run themselves instead of paying monthly.

## How to answer
- Build a small cost table: domain / hosting / database / services → paid price vs. free option.
- Name the catch for each free tier (sleep on idle, storage/request limits, can be revoked) — free tiers are fine for launch and MVPs, not guaranteed forever.
- Always tell the user to keep their own backup (code in git, `pg_dump`/`.sql` of the DB) so nothing is locked into a free provider.
- Static sites: GitHub Pages / Cloudflare Pages are usually the simplest zero-cost path.
