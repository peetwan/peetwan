<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:e8615f,100:9b2233&text=Chanut%20Wannasarnmetha&fontSize=44&fontColor=efe6cf&fontAlignY=36&desc=Applied%20AI%20Engineer%20%2F%20Builder%20%C2%B7%20Thailand&descSize=17&descAlignY=58&animation=fadeIn" alt="Chanut Wannasarnmetha" />

<div align="center">

<a href="https://chanut.dev">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=2600&pause=900&center=true&vCenter=true&width=640&height=42&color=e8615f&lines=Applied+AI+Engineer+%2F+Builder;I+learn+by+shipping;AI+is+my+study+partner;Based+in+Thailand" alt="about me" />
</a>

<p>
  🇹🇭 &nbsp;Applied AI Engineer / Builder &nbsp;·&nbsp; UTC+7<br/>
  <sub>Not a classically trained ML engineer. I build things because something was bugging me and I wanted it to stop.</sub>
</p>

<p>
  <a href="https://chanut.dev">🌐 chanut.dev</a> &nbsp;·&nbsp;
  <a href="https://cv.chanut.dev">📄 CV</a> &nbsp;·&nbsp;
  <a href="https://github.chanut.dev">💻 GitHub</a> &nbsp;·&nbsp;
  <a href="https://fb.chanut.dev">Facebook</a>
</p>

</div>

---

## About me

I'm not a classically trained ML engineer. I build things because something was bugging me and I wanted it to stop, figuring out the parts I'm missing as I go. Most of what I make ships: an open-source package, production storefronts, and a multi-tenant SaaS.

I got into Super AI Engineer (SS06), and that pulled me into a long run of hackathons. I know the basics and work out the rest as I go, usually with an AI next to me to explain the parts I'm missing and help me build.

Mostly I make things because something was bugging me and I wanted it to stop. A lot of that stays private — small tools for myself, experiments I'm still poking at. The public repos below are just the parts I'm happy to show.

## What I've built (the public stuff)

### [ThaiEDA](https://github.com/peetwan/thaieda) · [PyPI](https://pypi.org/project/thaieda/)
One-line AutoEDA and smart cleaning built for Thai and mixed-language data. `run(df)` generates HTML
reports with charts, missing-value analysis, outlier detection, and correlation matrices — all in Thai.
Smart cleaning handles Buddhist-era dates, Thai numerals, mojibake (ftfy), and Thai tokenization
(pythainlp). **1,000+ tests**, CI/CD with ruff + pytest across Python 3.11–3.13. v2.3.0 on PyPI.
*Python, pandas, scikit-learn, pythainlp, hatchling.*

### [Hidden Siam](https://github.com/peetwan/travel_hack_04) · [live demo](https://travelhack04-copy-3-production.up.railway.app)
I was tired of generic "top 10 places" travel lists, so I made a planner where eight AI agents do the
arguing for you. You give it the kind of trip you want, and they go back and forth over ~91 spots and
work out a route while you watch. Built it for a hackathon. *Next.js, Vercel AI SDK.*

### [autofollowdown](https://github.com/peetwan/autofollowdown)
I kept reading about model compression and wanted to actually see it happen instead of nodding along.
So this shrinks a model — quantize, prune, distill — and measures what you really lose in size, speed,
and accuracy. Nothing faked; it changes real weights and reports real numbers. *Python.*

### [fahmai-enterprise-data-agent](https://github.com/peetwan/fahmai-enterprise-data-agent)
An agent that answers questions over a messy company database. The common questions go through
hand-written SQL; the weird ones go to a plan-then-check agent. It has access control and some
guardrails against prompt injection. I wrote myself a whole study course while figuring it out.
*Python, SQLite/DuckDB, Qwen on HPC.*

### [senseflow](https://github.com/peetwan/senseflow) & [gutmagotchi](https://github.com/peetwan/gutmagotchi-stress-companion)
Two little Arduino UNO Q gadgets. One watches your posture and focus and turns it into a desk pet; the
other reads your stress without touching you and feeds it to a Tamagotchi-style cat. The audio side
runs on the board on purpose — I didn't want anything leaving the device. *C++, Python, BLE.*

### [agOS](https://github.com/peetwan/agOS)
I got sick of re-explaining myself to AI tools every session, so I gave the Gemini CLI plus Obsidian a
real memory. It remembers my notes and my opinions, and pushes back instead of just agreeing with me.

<details>
<summary>older stuff — Kaggle templates, object detection, Jetson edge notes…</summary>

<br/>

- [5DomainsHackathon_Pangpuriye](https://github.com/peetwan/5DomainsHackathon_Pangpuriye) — Super AI Engineer prep: 5 Kaggle problems turned into reusable notebook templates, all commented in Thai.
- [PangpuriyeT](https://github.com/peetwan/PangpuriyeT) — an object-detection sandbox (PyTorch, Faster R-CNN, GradCAM) I used to learn how to keep experiments clean.
- [saie2026-handbook](https://github.com/peetwan/saie2026-handbook) — team notes on Jetson Nano FPS / FPS-per-watt.
- [FiarDesignOrderBot](https://github.com/peetwan/FiarDesignOrderBot) — a LINE bot that reads orders out of a group chat and files them.

</details>

## Open source contributions

- **[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent/pull/55545)** — co-author on PR #55545 (`fix(tui_gateway): prevent Desktop WS disconnect under GIL pressure`). The Desktop WebSocket was dropping during long, GIL-heavy agent turns because the asyncio event loop was starved past the 20s ping deadline. My fix was salvaged from earlier PRs (#51841, #54287) and merged into `main` with authorship preserved via `AUTHOR_MAP`.

## 🔒 The private stuff (where most of my time goes)

Most of what I build is private. Two projects have eaten most of my year. I'll keep them nameless, but
here's the shape of them.

<img width="100%" src="https://raw.githubusercontent.com/peetwan/peetwan/main/assets/card-1.svg?v=2" alt="A booking platform built around LINE — private, multi-tenant, real-time. A multi-tenant platform where customers book and pay without leaving the app; each shop gets its own page, calendar, dashboard, and analytics off one shared backend. The hard parts stay private." />

<img width="100%" src="https://raw.githubusercontent.com/peetwan/peetwan/main/assets/card-2.svg?v=2" alt="An automated trading system — private, automated, real-time, strategy classified. A multi-asset setup on a perps DEX: a real-time fleet of services (execution engine, analytics, bots, dashboards). The strategy and signals stay in the vault." />

Past those two there's a stack of smaller private tools I built just to stop something from annoying me
— an agent that does my morning market reading and drops it into Notion, a few automations, a hackathon
build that walks people through a scary, paperwork-heavy moment in plain language. Nothing fancy, all
useful. Happy to talk through any of it; just don't ask me for the trading signals. 😄

## How I work

I learn by building. If I don't get how something works, I start making it and figure it out on the
way — with an AI explaining the bits I'm missing, then I write it back in my own words so it sticks. I
keep things simple, I'd rather measure something on real hardware than trust a number I skimmed, and I
keep things on-device when I can.

## Tools

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,nextjs,react,nodejs,cpp,arduino,pytorch,tailwind,vercel,git,obsidian&perline=12" alt="tools I use" />
</div>

<p align="center">
  <sub>also: <code>LLMs / agents / RAG</code> · <code>Vercel AI SDK</code> · <code>DuckDB</code> · <code>edge AI · Jetson · BLE</code> · <code>LINE / LIFF</code> · <code>Gemini CLI · Claude Code · Cursor · Antigravity · Hermes Agents</code></sub>
</p>

## Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/peetwan/peetwan/output/snake-dark.svg" />
    <img width="100%" src="https://raw.githubusercontent.com/peetwan/peetwan/output/snake-light.svg" alt="contribution snake" />
  </picture>

  <br/><br/>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=peetwan&hide_border=true&background=00000000&ring=e8615f&fire=e8615f&currStreakLabel=e8615f&currStreakNum=efe6cf&sideNums=efe6cf&sideLabels=9a948a&dates=9a948a&stroke=2c2822" />
    <img height="150" src="https://streak-stats.demolab.com/?user=peetwan&hide_border=true&background=00000000&ring=e8615f&fire=e8615f&currStreakLabel=e8615f&currStreakNum=24292f&sideNums=24292f&sideLabels=57606a&dates=57606a&stroke=d0d7de" alt="contribution streak" />
  </picture>
</div>

## Say hi

I'm based in Thailand and always up for building something weird with AI and hardware.

<div align="center">

[🌐 chanut.dev](https://chanut.dev) &nbsp;·&nbsp;
[📄 CV](https://cv.chanut.dev) &nbsp;·&nbsp;
[📧 Email](mailto:peet.wannasarnmetha@gmail.com) &nbsp;·&nbsp;
[💻 GitHub](https://github.chanut.dev) &nbsp;·&nbsp;
[Facebook](https://fb.chanut.dev)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:9b2233,100:e8615f" alt="" />