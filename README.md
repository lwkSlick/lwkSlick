<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD,4B0082,7B2FBE,3D007A&height=200&section=header&text=lwkSlick&fontSize=80&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Minecraft%20Developer%20%7C%20Content%20Creator%20%7C%20Modder&descAlignY=58&descSize=18" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=9B59B6&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Tinkering+with+Minecraft+Mods;Running+an+SMP+Server;Learning+Django+%26+Python;Content+Creator+%7C+Community+Builder)](https://git.io/typing-svg)

</div>

---

<div align="center">

![Location](https://img.shields.io/badge/Location-Online-6A0DAD?style=flat-square&logo=googlemaps&logoColor=white)
![Status](https://img.shields.io/badge/Status-Open%20To%20Work-4B0082?style=flat-square&logo=statuspage&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-lwkSlick-7B2FBE?style=flat-square&logo=github&logoColor=white)
![Profile Views](https://komarev.com/ghpvc/?username=lwkSlick&color=6A0DAD&style=flat-square&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/lwkSlick?style=flat-square&color=4B0082&logo=github&logoColor=white&label=Followers)
![GitHub Stars](https://img.shields.io/github/stars/lwkSlick?style=flat-square&color=7B2FBE&logo=github&logoColor=white&label=Stars)

</div>

---

## 🧑‍💻 About Me

```yaml
name: lwkSlick
role: Minecraft Content Creator & Developer (still learning)
focus:
  - Tinkering with Fabric mods (Java)
  - Building stuff with Django / Python
  - Running & managing a Minecraft SMP server
  - Growing a community and making content
platforms:
  - Instagram
  - TikTok
  - Discord (300+ members)
honest_take:
  - Learning as I go — mostly hands-on
  - Server admin is where I'm most comfortable
  - Code side is a work in progress, but shipping anyway
open_to:
  - Collabs with other Minecraft creators
  - Content partnerships
  - Feedback on my projects
```

---

## ⚙️ Tech Stack

<div align="center">

### Languages
[![Languages](https://skillicons.dev/icons?i=java,python,js,html,css&theme=dark)](https://skillicons.dev)

### Frontend & Frameworks
[![Frontend](https://skillicons.dev/icons?i=django,bootstrap,html,css&theme=dark)](https://skillicons.dev)

### Backend & Databases
[![Backend](https://skillicons.dev/icons?i=python,sqlite,mysql,django&theme=dark)](https://skillicons.dev)

### Cloud, DevOps & Tooling
[![DevOps](https://skillicons.dev/icons?i=git,github,linux,bash,vscode,gradle&theme=dark)](https://skillicons.dev)

</div>

---

## 🤖 Domain Expertise

| Domain | Proficiency | Details |
|:---|:---:|:---|
| Minecraft Server Admin | ███████░░░ Comfortable | Paper/Spigot, plugins, log digging, player management |
| Content Creation | ███████░░░ Comfortable | Short-form video, Discord community, bot setup |
| Fabric Mod Development | █████░░░░░ Learning | YACL config, ModMenu, event hooks — figuring it out |
| Django / Python | █████░░░░░ Learning | Multi-role auth, templates, Bootstrap theming |
| Java (Minecraft) | █████░░░░░ Learning | Client-side mods, following documentation closely |
| Linux / Bash | ████░░░░░░ Basic | Server commands, file management, reading logs |
| Security & Anti-Cheat | ███░░░░░░░ Dabbling | UUID migration, spotting suspicious activity |

---

## 🚀 Featured Projects

<details>
<summary><b>⚔️ GhostMode — Fabric Client Mod</b></summary>

<br>

A privacy-first client-side Fabric mod built for Minecraft content creators. Designed to mask sensitive personal information during live streams and recordings — server IPs, chat content, and player data — without disrupting normal gameplay.

| Attribute | Details |
|:---|:---|
| **Stack** | Java · Fabric API · YACL 3.8.2 · ModMenu 17.0.0 |
| **Minecraft Version** | 1.21.11 (Fabric) |
| **Architecture** | Client-side only · Mixin-free render swap approach |
| **Key Features** | Chat masking · Server IP render override · Configurable keybind (J) · YACL config screen |
| **Security** | Zero server-side footprint · No data mutation on saved server list |
| **Package** | `com.lwkslick.ghostmode` |
| **Repository** | [github.com/lwkSlick/ghostmode](https://github.com/lwkSlick) |

GhostMode was engineered with a strict constraint: mask sensitive data at the render layer only, never mutate persisted state. An early mixin approach that modified `ServerInfo.address` caused data loss to the server list and was scrapped. The final architecture intercepts rendering calls and swaps display text at runtime, keeping the underlying data completely intact. Integrates with ModMenu for in-game settings and exposes a fully featured YACL configuration screen.

</details>

---

<details>
<summary><b>🎯 HitBox Reveal — Fabric Client Mod</b></summary>

<br>

A Fabric client-side mod that exposes hitbox visualisation for entities in Minecraft, built as a competitive PvP utility for SMP players and content creators showcasing PvP mechanics.

| Attribute | Details |
|:---|:---|
| **Stack** | Java · Fabric API · Fabric Renderer |
| **Minecraft Version** | 1.21.x (Fabric) |
| **Architecture** | Client-side · Render pipeline injection |
| **Key Features** | Per-entity hitbox toggle · Custom overlay colours · Minimal performance overhead |
| **Use Case** | PvP training · Content creation · Competitive SMP |
| **Repository** | [github.com/lwkSlick/hitboxreveal](https://github.com/lwkSlick) |

HitBox Reveal hooks into Minecraft's render pipeline to draw accurate entity hitboxes as persistent overlays. Designed for minimal frame impact, the mod targets PvP players who need precise collision awareness and content creators demonstrating Minecraft's combat mechanics. Fully configurable and toggle-able in-session.

</details>

---

<details>
<summary><b>📊 PvP Stats — Player Statistics Tracker</b></summary>

<br>

A server-side statistics tracking system for Minecraft SMP servers, logging PvP performance data per player and surfacing leaderboards and analytics for community engagement.

| Attribute | Details |
|:---|:---|
| **Stack** | Java · Paper API · SQLite / MySQL |
| **Target Platform** | Paper / Spigot 1.21.x |
| **Architecture** | Server-side plugin · Event-driven stat collection |
| **Key Features** | Kill/death tracking · Streak detection · Leaderboard commands · Per-class stats |
| **Scale** | Designed for SMP communities (10–100 concurrent players) |
| **Repository** | [github.com/lwkSlick/pvpstats](https://github.com/lwkSlick) |

PvP Stats was built to give SMP communities a competitive edge — tracking kills, deaths, streaks, and class performance across sessions. Data is persisted to SQLite with optional MySQL support for larger deployments. Leaderboard commands are accessible in-game and designed for content clipping, giving creators ready-made competitive narrative for their videos.

</details>

---

## 💼 Experience

**Minecraft Content Creator & Developer** · *Independent*
`2022 – Present`

Running a Minecraft SMP, making content, and slowly picking up development along the way. Still learning, but building real things.

- Built some Fabric client mods (with a lot of trial and error)
- Grew a Discord from scratch to 500+ members and set up bots to keep it running
- Post short-form Minecraft content on Instagram and TikTok
- Putting together a Django web app as a side project — learning as I build

![Java](https://img.shields.io/badge/Java-6A0DAD?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-4B0082?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-7B2FBE?style=flat-square&logo=django&logoColor=white)
![Fabric](https://img.shields.io/badge/Fabric_API-3D007A?style=flat-square&logo=minecraft&logoColor=white)
![Paper](https://img.shields.io/badge/Paper_MC-6A0DAD?style=flat-square&logo=minecraft&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-4B0082?style=flat-square&logo=linux&logoColor=white)

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|:---:|:---|
| 🔧 Mod Tinkerer | Made some Fabric mods that actually work |
| 👥 Community Builder | Built a Discord from zero to 500+ members |
| 📱 Content Creator | Posting Minecraft content on Instagram & TikTok |
| 🌐 Hobby Dev | Django web app in progress — learning by doing |

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=lwkSlick&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0D0D&title_color=9B59B6&icon_color=7B2FBE&text_color=C9B8E8"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lwkSlick&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=9B59B6&text_color=C9B8E8"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=lwkSlick&theme=midnight-purple&hide_border=true&background=0D0D0D&ring=9B59B6&fire=7B2FBE&currStreakLabel=9B59B6"/>

</div>

---

## 🏅 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=lwkSlick&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=lwkSlick&bg_color=0D0D0D&color=9B59B6&line=7B2FBE&point=C9B8E8&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lwkSlick/lwkSlick/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lwkSlick/lwkSlick/output/github-contribution-grid-snake.svg"/>
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/lwkSlick/lwkSlick/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

---

## 🎯 Current Focus

```yaml
current_focus:
  learning:
    - How Fabric mods actually work under the hood
    - Django — templates, views, making it not break
    - Reading more documentation before asking for help
  building:
    - GhostMode — privacy mod for streamers
    - PvP Stats — kill/death tracker for my SMP
    - Django web app for my server (work in progress)
  exploring:
    - OBS workflows for recording SMP sessions
    - Python scripting for server log stuff
    - Whatever the next thing is
  open_to:
    - Collabs with other Minecraft creators
    - Feedback on my projects
    - Anyone who wants to play on the SMP
```

---

## 🤝 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-lwkSlick-6A0DAD?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lwkSlick)
[![Discord](https://img.shields.io/badge/Discord-Community-4B0082?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/lwkSlick)
[![TikTok](https://img.shields.io/badge/TikTok-lwkSlick-7B2FBE?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@lwkSlick)
[![Instagram](https://img.shields.io/badge/Instagram-lwkSlick-3D007A?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/lwkSlick)

</div>

---

<div align="center">

*"Still figuring it out — but shipping anyway."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD,4B0082,7B2FBE,3D007A&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
