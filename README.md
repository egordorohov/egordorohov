<h1 align="center">Egor Dorohov</h1>

<p align="center">
  <b>Full-stack vibe-coder</b> · real-time services, Telegram apps, self-hosted infrastructure
</p>

<p align="center">
  <a href="https://t.me/egordoroh2"><img src="https://img.shields.io/badge/Telegram-@egordoroh2-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:egordoroh2@xamchat.fun"><img src="https://img.shields.io/badge/Mail-egordoroh2@xamchat.fun-6A6AE0?style=flat-square&logo=maildotru&logoColor=white" alt="Email"></a>
</p>

---

### About

I build things end to end: backend, client, and the server they run on.
Most of my projects are real-time — WebSocket game rooms, chat, voice calls — and
they live on my own VPS: nginx, Docker, PostgreSQL, Redis, TLS, deploys, logs and
outages included.

I like problems where the fix is found in a log file and proven with a measurement,
not guessed.

### Stack

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Backend** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-000000?style=flat-square&logo=socketdotio&logoColor=white)

**Clients** &nbsp;
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**Infrastructure** &nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

### Selected work

**[durak](https://github.com/egordorohov/durak)** — multiplayer card game (Telegram Mini App)
> FastAPI + WebSocket rooms, PostgreSQL and Redis, bot opponents that fill empty seats,
> ranks and cosmetics. Runs in production on my own server behind nginx.

**[delivery](https://github.com/egordorohov/delivery)** — storefront and checkout prototype
> Static front-end: catalog, cart, order flow. No framework, just HTML, CSS and JavaScript.

### In private

**A messenger, built solo, top to bottom** — private for now, but there's a lot in it.

<p>
  <img src="screens/chats.png" width="200" alt="chat list">
  <img src="screens/incoming-call.png" width="200" alt="incoming call">
  <img src="screens/active-call.png" width="200" alt="active call">
  <img src="screens/schedule.png" width="200" alt="schedule mini app">
</p>

- **End-to-end encryption** — one identity keypair per account (not per device), device
  linking and key transfer done over QR, so a new device joins an encrypted conversation
  instead of starting a blank one.
- **Voice channels, Discord-style** — mesh WebRTC, screen share, a live speaking-now
  indicator, a shared drawing board, and small multiplayer games (blackjack, poker,
  Wordle) playable right inside the call.
- **Calls that survive bad networks** — WebRTC tuning based on real device measurements
  rather than defaults, a TURN relay of my own, and an in-app VPN tab (Xray-core) for
  when the network itself is the problem.
- **Four clients, one account** — Android (Kotlin/Compose), a web client, and a desktop
  app (Tauri) with self-updating builds, all talking to the same backend and the same
  end-to-end keys.
- **Mail on my own domain** — inbound SMTP wired straight into the chat: pick a mailbox
  name in a bot conversation, and mail to it shows up as a message, HTML and
  attachments included.
- **Bots and Mini Apps** — a Telegram-style bot platform (webhooks, inline keyboards,
  scoped tokens) hosting a schedule bot, a card game, and a couple of in-house tools.
- **A Telegram gift-number sniping bot** — one monolithic Python file (thousands of
  lines, everything handled by hand: multi-account management, scheduled jobs,
  monitoring, an admin panel) that watches Telegram's collectible gifts and grabs
  ones with a good number the moment they're mintable — think `PlushPepe-67`. Caught
  around 20 of them so far, worth roughly 5000 TON.

### Activity

<p>
  <img src="https://img.shields.io/github/followers/egordorohov?style=flat-square&label=followers&color=6A6AE0" alt="followers">
  <img src="https://img.shields.io/github/stars/egordorohov?style=flat-square&label=stars&color=6A6AE0" alt="stars">
  <img src="https://img.shields.io/badge/open%20to-work%20%26%20freelance-3DDC84?style=flat-square" alt="open to work">
</p>
