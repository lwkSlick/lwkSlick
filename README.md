<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD,4B0082,7B2FBE,3D007A&height=200&section=header&text=lwkSlick&fontSize=80&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Minecraft%20Developer%20%7C%20Content%20Creator%20%7C%20Modder&descAlignY=58&descSize=18" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=9B59B6&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Building+Minecraft+Mods+%26+Tools;Full+Stack+Django+Developer;SMP+Server+Administrator;Content+Creator+%7C+Community+Builder)](https://git.io/typing-svg)

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
role: Minecraft Developer & Content Creator
focus:
  - Fabric mod development (Java)
  - Full Stack web development (Django / Python)
  - Minecraft SMP server administration
  - Community building & content creation
platforms:
  - Instagram
  - TikTok
  - Discord (300+ members)
engineering_mindset:
  - User-first product thinking
  - Clean, maintainable code architecture
  - Security-conscious server administration
  - Data-driven player experience design
open_to:
  - Mod commissions & collaborations
  - Open source contributions
  - Content partnerships
  - Developer roles (backend / full stack)
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
| Fabric Mod Development | ████████░░ Advanced | Mixins, YACL config, ModMenu, event hooks |
| Django Web Development | ███████░░░ Intermediate | Multi-role auth, template inheritance, Bootstrap |
| Minecraft Server Admin | █████████░ Expert | Paper/Spigot, plugin ecosystems, log analysis |
| Java (Minecraft) | ████████░░ Advanced | Client-side mods, rendering, packet interception |
| Python | ███████░░░ Intermediate | Django, scripting, log parsing, automation |
| Content Creation | █████████░ Expert | Short-form video, community management, Discord |
| Linux / Bash | ███████░░░ Intermediate | Server management, scripting, file systems |
| Security & Anti-Cheat | ██████░░░░ Developing | UUID migration, exploit detection, IP analysis |

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

Building a full creative and technical operation around Minecraft — from server infrastructure and mod development to short-form video content and community management.

- Operate and administrate a live Minecraft SMP server on Paper/Spigot with custom plugin configurations
- Developed client-side Fabric mods in Java targeting content creator and PvP use cases
- Grew a Discord community from 0 to 300+ members with structured bots (Sapphire, ProBot, Carl-bot)
- Produce and publish short-form Minecraft content across Instagram and TikTok
- Engineered a multi-role Django web application (Administrator / User / Guest) with Bootstrap theming
- Conduct server security reviews including log analysis, UUID auditing, and exploit detection

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
| 🎮 SMP Operator | Founded and operate a live Minecraft SMP with active player base |
| 🔧 Mod Author | Released production Fabric mods targeting real creator pain points |
| 👥 Community Builder | Scaled Discord server to 300+ engaged members |
| 🔐 Security Researcher | Identified and mitigated x-ray exploit & UUID probing on live server |
| 📱 Content Creator | Active short-form creator across Instagram & TikTok |
| 🌐 Full Stack Developer | Shipped multi-role Django web app with scoped Bootstrap theming |

</div>

---

## 📜 Certifications & Profiles

<div align="center">

### Coding Profiles

[![LeetCode](https://img.shields.io/badge/LeetCode-lwkSlick-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/lwkSlick)
[![HackerRank](https://img.shields.io/badge/HackerRank-lwkSlick-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://hackerrank.com/lwkSlick)
[![GeeksForGeeks](https://img.shields.io/badge/GeeksForGeeks-lwkSlick-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://geeksforgeeks.org/user/lwkSlick)

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
    - Advanced Fabric mixin patterns
    - Minecraft render pipeline internals
    - REST API design with Django REST Framework
    - PostgreSQL for production Django deployments
  building:
    - GhostMode v2 — expanded privacy controls
    - PvP Stats plugin — leaderboard web dashboard
    - SMP server web portal (Django)
  exploring:
    - Kotlin for Minecraft plugin development
    - OBS scripting for automated content workflows
    - Discord bot development (Python / discord.py)
  open_to:
    - Fabric / Paper mod commissions
    - Content collaboration with other creators
    - Backend / full stack developer roles
    - Open source Minecraft tooling contributions
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

*"Ship things that work. Build things that matter. Document everything."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD,4B0082,7B2FBE,3D007A&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
