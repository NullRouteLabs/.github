# NullRouteLabs
NullRouteLabs is the home of my personal infrastructure empire.
Everything here was built to be fast, minimal, reliable, and to not suck ass like 99% of the garbage floating around.

This isn't another "todo app v6" portfolio. This is a full stack of services running across my own servers, under my own domains, controlled by me — not some bloated cloud corporation.

---

## What This Shit Is
- **Smart Control Center** (`c2.zer0.sh`)
  Manage my VPS fleet, issue remote commands, monitor node health, and flex with a real terminal UI — not some dumbass web dashboard.

- **Arch Update Monitor** (`arch.zer0.sh`)
  Tracks when I last updated my Arch setups and screams at me if something goes wrong after an upgrade. Panic banners included.

- **File Hosting** (`files.zer0.sh`)
  Upload files, get direct links, host screenshots.

- **Pastebin** (`bin.zer0.sh`)
  Minimal pastebin service for me and trusted friends. Supports expiring pastes and optional encryption because fuck handing your snippets to strangers.

- **Mail System** (`webmail.zer0.sh`)
  Webmail client hooked into Mailgun, made for flexing custom domains — not for sending nuclear launch codes (yet).

- **Status & Metrics** (`stats.zer0.sh`)
  Live uptime, service usage counts, donation status, and server costs. If shit breaks, it'll tell me.

---

## Why Does This Exist?
Because I was tired of seeing clowns copy-pasting the same garbage into GitHub and calling themselves "full-stack engineers."
I wanted to actually **build real infrastructure**, from the ground up — services I can trust because **I made them**, not because a $10 billion startup slapped "secure" on a marketing page.

---

## Tech Stack
- Go (backend services, WebSocket clients, REST APIs)
- Next.js (frontend sites)
- PostgreSQL (databases when needed)
- Cloudflare (proxying, DNS, storage)
- Mailgun (email reception / delivery)
- Docker / docker-compose (deployments)

---

## Security Notes
- TLS everywhere — no plaintext bullshit.
- Token-based API auth between services.
- Agents and services validate each other with signed tokens.
- Secrets are stored in env files or vaults — not hardcoded like a skid.
- If you find a vulnerability, report it properly. Don't be a dickhead.

---

## Donations?
If you somehow use one of my services and want to cover some server bills, cool. If not, also cool.
I'm building this for myself first — flexing is just a nice bonus.

Details at [`stats.zer0.sh`](https://stats.zer0.sh) when it’s live in 2034 or later.
