<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5f,100:2dd4bf&height=180&section=header&text=%C3%96nderhan%20%C4%B0%C5%9Fleko%C4%9Flu&fontSize=42&fontColor=f8fafc&fontAlignY=35&desc=autonomous%20systems%20%C2%B7%20risk-first%20automation%20%C2%B7%20developer%20tools&descSize=16&descAlignY=55" width="100%" alt="header"/>

### Merhaba / Hi 👋

I build **autonomous systems that are allowed to fail safely** — trading agents with
hard-coded risk gates, portfolio automation that writes its own daily reports, and
tooling that turns messy feedback into structured data.

- 🔭 Currently: an autonomous crypto perp-futures trading agent, and a Claude-managed
  portfolio pipeline for Turkish markets
- 🧪 I don't ship a strategy I haven't measured: preregistered acceptance gates,
  locked columns, limited retry budgets
- 🛡️ House rules I code by: **hard limits live in code, not config** · **LLMs design,
  deterministic code executes** · **kill switches run out-of-band**

---

### 🚀 Selected work

| Project | What it is | Stack |
|---|---|---|
| **MessiahGate** | Autonomous crypto perpetual-futures trading agent on top of freqtrade — adds the layers freqtrade lacks: mandatory hard-coded risk gates, an out-of-band dead-man kill switch (separate process, separate API key), and Turkish-localized reporting. Strategy decisions come from a local FreqAI model; every experiment is preregistered with fixed acceptance criteria before it runs. | Python · freqtrade/FreqAI · LightGBM · systemd |
| **claude-portfoy** | Claude-managed portfolio automation for BIST equities + gold: daily data pipeline, a rules engine that enforces risk limits before any trade is recorded, KAP/RSS news aggregation, headless AI analysis sessions on a schedule, and a self-rendered dashboard — 175+ tests. | Python · systemd timers · Claude Code |
| **BuildLoop** | Build & playtest tracker for indie game developers — Discord-first invite flow, slash-command `/feedback` and `/bug` capture, signed time-limited download URLs, and an async integrity-check queue for uploads. | TypeScript · Node.js · Discord API · BullMQ/Redis · Drizzle |

> 🔓 These repos are private while they harden; they're being opened up piece by piece.

---

### 🧰 Tools I reach for

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
<img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
<img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Linux%20%2F%20systemd-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas"/>
<img src="https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge&logoColor=white" alt="LightGBM"/>
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code"/>
</p>

---

### 📊 GitHub

<p>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ondrhn&show_icons=true&count_private=true&hide_border=true&theme=github_dark&bg_color=00000000">
  <img src="https://github-readme-stats.vercel.app/api?username=ondrhn&show_icons=true&count_private=true&hide_border=true&bg_color=00000000" alt="GitHub stats" height="165"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ondrhn&layout=compact&hide_border=true&theme=github_dark&bg_color=00000000">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ondrhn&layout=compact&hide_border=true&bg_color=00000000" alt="Top languages" height="165"/>
</picture>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2dd4bf,50:1e3a5f,100:0f172a&height=100&section=footer" width="100%" alt="footer"/>
