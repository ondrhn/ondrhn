<img src="https://raw.githubusercontent.com/ondrhn/ondrhn/master/assets/header.svg?v=3" width="100%" alt="Önderhan İşlekoğlu — full-stack developer, front-end at heart · Vue & TypeScript · open source contributor"/>

### Hi, I'm Önderhan 👋

Full-stack developer from Istanbul, front-end at heart. Most of my work is **TypeScript, Vue 3 and the
tooling around it**, with Node.js and Python on the backend. I like small, well-tested changes and code
that fails loudly.

```yaml
name: "Önderhan İşlekoğlu"
handle: ondrhn
location: "Istanbul, Türkiye"
focus:
  - "Vue 3 · TypeScript · Vite"
  - "Node.js services and developer tooling"
  - "Python automation with guardrails enforced in code"
open_source: "Vue ecosystem first — core, devtools, router, pinia"
house_rules:
  - "Hard limits live in code, not config"
  - "Reproduce before fixing, test before pushing"
  - "One change per pull request"
```

---

### 🟢 Open source

Bug fixes and small improvements to the libraries I use every day, Vue ecosystem first. One row per project, latest change on top — [all pull requests →](https://github.com/pulls?q=is%3Apr+author%3Aondrhn+-user%3Aondrhn+sort%3Acreated-desc)

| Project | Latest change | Pull requests |
|---|---|---|
| [vuejs/pinia](https://github.com/vuejs/pinia) | Resolve the default Nuxt `storesDirs` against every layer, so stores inside layers are auto-imported again | [#3185](https://github.com/vuejs/pinia/pull/3185) |
| [vuejs/core](https://github.com/vuejs/core) | Stop patching the native array iterator when iterating a reactive array, which was slowing down spread and `Array.from` page-wide | [#15645](https://github.com/vuejs/core/pull/15645) · [#15640](https://github.com/vuejs/core/pull/15640) · [#15637](https://github.com/vuejs/core/pull/15637) · <sub>[+3 more](https://github.com/vuejs/core/pulls?q=is%3Apr+author%3Aondrhn+sort%3Acreated-desc)</sub> |
| [vueuse/vueuse](https://github.com/vueuse/vueuse) | Roll back `useRouteQuery` / `useRouteParams` when a navigation guard cancels the change | [#5641](https://github.com/vueuse/vueuse/pull/5641) |
| [vuejs/router](https://github.com/vuejs/router) | Explain why a shared path prefix alone does not make a link active | [#2802](https://github.com/vuejs/router/pull/2802) |
| [vuejs/devtools](https://github.com/vuejs/devtools) | Bump Electron to v42 so the binary installs on Node.js 26 | [#1137](https://github.com/vuejs/devtools/pull/1137) |
| [typeorm/typeorm](https://github.com/typeorm/typeorm) | Handle rejected lazy relation loads in the query builder | [#12866](https://github.com/typeorm/typeorm/pull/12866) |
| [huntabyte/bits-ui](https://github.com/huntabyte/bits-ui) | Keep the day period after typing the hour in 12-hour `TimeField` | [#2148](https://github.com/huntabyte/bits-ui/pull/2148) |

---

### 🚀 Selected work

| Project | What it is | Stack |
|---|---|---|
| [**contrib-policy**](https://github.com/ondrhn/contrib-policy) | Reads a project's contribution rules before a pull request goes out and answers one question: may this change be sent here, and on what terms? Looks at CONTRIBUTING, AI policies, PR templates, foundation rules and the repository settings, then says GO, GO-DECLARE or STOP and quotes the exact sentence that decided it. Works as a skill for coding agents or as a plain command; no model call, just bash. Checked against 78 real repositories, then attacked as a stranger's file would attack it: invisible characters inside words, look-alike letters, HTML tricks, NUL bytes and escape sequences, every way of spelling `gh pr create` a hook might miss. What got through and what changed is written up in the repo. | Bash · curl · jq · awk |
| **BuildLoop** | Build & playtest tracker for indie game developers — Discord-first invite flow, slash-command `/feedback` and `/bug` capture, signed time-limited download URLs, and an async integrity-check queue for uploads. | TypeScript · Node.js · Discord API · BullMQ/Redis · Drizzle |
| **MessiahGate** | Crypto perpetual-futures trading agent on top of freqtrade — adds the layers freqtrade lacks: mandatory hard-coded risk gates, an out-of-band dead-man kill switch (separate process, separate API key), and localized reporting. Every experiment is preregistered with fixed acceptance criteria before it runs. | Python · freqtrade/FreqAI · LightGBM · systemd |
| **messiah-portfoy** | Portfolio automation for BIST equities + gold: daily data pipeline, a rules engine that enforces risk limits before any trade is recorded, KAP/RSS news aggregation, scheduled analysis jobs, and a self-rendered dashboard — 175+ tests. | Python · systemd timers · SQLite |

> 🔓 contrib-policy is public. The other three are private while they harden; they're being opened up piece by piece.

---

### 🧰 Tools I reach for

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/Vue.js-41B883?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/C%23%20%2F%20.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C# / .NET"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
<img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Linux%20%2F%20systemd-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

### 📊 GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=ondrhn&theme=github-dark-blue&hide_border=true&background=00000000">
  <img src="https://streak-stats.demolab.com?user=ondrhn&hide_border=true&background=00000000" alt="GitHub streak" height="165"/>
</picture>

<a href="https://github.com/ondrhn"><img src="https://ghchart.rshah.org/41b883/ondrhn" alt="Contribution graph" width="100%"/></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ondrhn/ondrhn/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/ondrhn/ondrhn/output/github-snake.svg" alt="Snake eating the contribution graph" width="100%"/>
</picture>

<img src="https://raw.githubusercontent.com/ondrhn/ondrhn/master/assets/footer.svg" width="100%" alt="footer"/>
