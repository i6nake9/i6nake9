<!--
  Profile README: DevOps / Platform Engineer edition
  Replace @i6nake9 links only if your GitHub username changes.
  The <details> terminal, animated SVG, and Mermaid diagrams are GitHub-safe Markdown/HTML.
-->

<div align="center">

<!-- HERO: custom animated terminal-like SVG, rendered directly by GitHub -->
<a href="https://github.com/i6nake9">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=2600&pause=800&color=35D0BA&center=true&vCenter=true&width=900&height=75&lines=ARTEM+BIELOV+%E2%80%94+DEVOPS+%2F+PLATFORM+ENGINEER;from+git+push+to+reliable+production;automate+the+system.+own+the+outcome." alt="Animated headline" />
</a>

<p>
  <a href="https://artembielov.com/"><img src="https://img.shields.io/badge/◉_STATUS-ONLINE_/_BUILDING-35D0BA?style=for-the-badge&labelColor=0D1117" alt="Status" /></a>
  <a href="https://github.com/i6nake9"><img src="https://img.shields.io/badge/⚙_MODE-SHIP_•_OBSERVE_•_IMPROVE-1F6FEB?style=for-the-badge&labelColor=0D1117" alt="Mode" /></a>
  <img src="https://komarev.com/ghpvc/?username=i6nake9&label=VISITORS&color=35D0BA&style=for-the-badge" alt="Profile views" />
</p>

</div>

<!-- Animated scanline divider -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />
</p>

## `~/identity` <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjM4OTBkOTgyMzEwMzkwYzJkODI4NzdmYzA5YjRmNmFmMzRmZmE3YiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/l0HlQ7LRalQqdWfao/giphy.gif" width="28" />

<table>
<tr>
<td width="58%" valign="top">

```bash
artem@production:~$ cat profile.yaml

name: Artem Bielov
location: Poland / Ukraine
role: DevOps-minded Full-Stack & Platform Engineer
motto: "Build it. Run it. Improve it."

mission:
  - Turn ideas into deployable products
  - Make releases predictable and repeatable
  - Replace fragile manual routines with automation
  - Build infrastructure that makes business move faster
```

</td>
<td width="42%" valign="top">

### Signal, not noise

I am a hands-on builder who works across the full delivery path—from application code to Linux servers, containers, reverse proxies, databases, and production operations.

Running product and e-commerce ventures taught me that a system is only useful when it is **reliable, maintainable, measurable, and cost-conscious**.

</td>
</tr>
</table>

<details>
<summary><b>▸ Open the production mindset</b></summary>
<br/>

```diff
+ Automate repeatable work.
+ Version infrastructure and deployment knowledge.
+ Design every service as something you may need to debug at 03:00.
+ Measure before optimizing.
- "It works on my machine" is not a deployment strategy.
```

</details>

## `~/delivery-pipeline`

<div align="center">

```text
┌──────────┐      ┌──────────────┐      ┌──────────────┐      ┌────────────────┐      ┌─────────────┐
│  WRITE   │ ───▶ │   VALIDATE   │ ───▶ │   PACKAGE    │ ───▶ │    RELEASE     │ ───▶ │   OBSERVE   │
│ code/ops │      │ lint/test/CI │      │ Docker image │      │ Linux + Nginx  │      │ logs/health │
└──────────┘      └──────────────┘      └──────────────┘      └────────────────┘      └──────┬──────┘
     ▲                                                                                          │
     └────────────────────────────── feedback → automate → improve ────────────────────────────┘
```

</div>

```mermaid
flowchart LR
    classDef source fill:#0d1117,stroke:#35D0BA,color:#e6edf3,stroke-width:2px
    classDef process fill:#161b22,stroke:#58A6FF,color:#e6edf3,stroke-width:2px
    classDef live fill:#13231e,stroke:#3FB950,color:#e6edf3,stroke-width:2px

    A["<b>01</b> 💻 Code"]:::source --> B["<b>02</b> 🔀 Git / GitHub"]:::source
    B --> C["<b>03</b> ✅ CI checks"]:::process
    C --> D["<b>04</b> 🐳 Container build"]:::process
    D --> E["<b>05</b> ☁️ Deploy to Linux"]:::live
    E --> F["<b>06</b> 🌐 Nginx gateway"]:::live
    F --> G["<b>07</b> 📦 App + data"]:::live
    G -. "telemetry + feedback" .-> A
```

## `~/stack --grouped`

<table>
<tr>
<td width="33%" valign="top">

### ☁️ Platform & Ops

<p>
<img src="https://skillicons.dev/icons?i=linux,docker,githubactions,nginx,gcp,ubuntu,bash,powershell&theme=dark" alt="Linux Docker GitHub Actions Nginx Google Cloud Ubuntu Bash PowerShell" />
</p>

`Linux` `Docker` `CI/CD` `Nginx`  
`Cloud` `Bash` `PowerShell` `Git`

</td>
<td width="33%" valign="top">

### 🧠 Services & Data

<p>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,ts,rust,postgres,mysql,redis,mongodb&theme=dark" alt="Node.js NestJS TypeScript Rust PostgreSQL MySQL Redis MongoDB" />
</p>

`Node.js` `NestJS` `TypeScript`  
`Rust` `PostgreSQL` `Redis`

</td>
<td width="33%" valign="top">

### 🎨 Product Layer

<p>
<img src="https://skillicons.dev/icons?i=nextjs,react,js,tailwind,shopify,figma&theme=dark" alt="Next.js React JavaScript Tailwind Shopify Figma" />
</p>

`Next.js` `React` `Shopify`  
`Tailwind` `Headless commerce`

</td>
</tr>
</table>

## `~/now`

<div align="center">

```text
╭──────────────────────────── CURRENT QUESTS ────────────────────────────╮
│                                                                         │
│  [████████░░]  Rust & systems programming                               │
│  [██████░░░░]  Kubernetes / cloud-native architecture                   │
│  [██████░░░░]  Infrastructure as Code                                   │
│  [███████░░░]  Observability, security & production operations          │
│                                                                         │
╰─────────────────────────────────────────────────────────────────────────╯
```

</div>

| Beacon | Current trajectory |
|:--|:--|
| `⚡ BUILD` | E-commerce and web products with an automation-first architecture |
| `🐳 OPERATE` | Containerized services, Linux deployments, reverse proxies, databases |
| `🦀 LEARN` | Rust, systems/embedded engineering, platform engineering practices |
| `🔭 EXPLORE` | IaC, Kubernetes, observability, resilient cloud-native delivery |

## `~/telemetry`

<div align="center">

<a href="https://github.com/i6nake9">
  <img height="185" src="https://github-readme-stats.vercel.app/api?username=i6nake9&show_icons=true&theme=transparent&hide_border=true&title_color=35D0BA&icon_color=58A6FF&text_color=C9D1D9&ring_color=35D0BA&include_all_commits=true&count_private=true" alt="GitHub statistics" />
</a>
<a href="https://github.com/i6nake9">
  <img height="185" src="https://github-readme-streak-stats.herokuapp.com/?user=i6nake9&theme=transparent&hide_border=true&ring=35D0BA&fire=35D0BA&currStreakLabel=35D0BA&sideLabels=C9D1D9&dates=8B949E&stroke=30363D" alt="GitHub contribution streak" />
</a>

<br/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=i6nake9&layout=compact&theme=transparent&hide_border=true&title_color=35D0BA&text_color=C9D1D9" alt="Top languages" />

</div>

## `~/connect`

<div align="center">

<a href="https://artembielov.com/"><img src="https://img.shields.io/badge/Website-artembielov.com-35D0BA?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Personal website" /></a>
<a href="https://dev.to/i6nake9"><img src="https://img.shields.io/badge/dev.to-i6nake9-0D1117?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to" /></a>
<a href="https://twitter.com/i6nake9"><img src="https://img.shields.io/badge/X-@i6nake9-0D1117?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="mailto:fleshartemka@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<sub>"If opportunities do not knock, build a door — then automate the deployment."</sub>

</div>

<!--
  OPTIONAL PREMIUM VISUAL:
  This requires a GitHub Actions workflow in your profile repository.
  Once configured, it animates your real contribution graph as a snake.

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/i6nake9/i6nake9/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/i6nake9/i6nake9/output/github-contribution-grid-snake.svg" />
    <img alt="Animated contribution snake" src="https://raw.githubusercontent.com/i6nake9/i6nake9/output/github-contribution-grid-snake.svg" />
  </picture>
-->

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=footer" alt="" />
  <br/>
  <code>system.status = "BUILDING · SHIPPING · AUTOMATING"</code>
</p>
