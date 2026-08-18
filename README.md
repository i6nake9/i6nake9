<!--
  ────────────────────────────────────────────────────────────────────────────
  Profile README — Artem Bielov (@i6nake9)
  DevOps / Platform Engineer — cinematic terminal edition v2
  All visuals are GitHub-safe (Markdown + allowed HTML + external SVG services).
  Replace "i6nake9" everywhere if the GitHub username changes.
  ────────────────────────────────────────────────────────────────────────────
-->

<div align="center">

<!-- ANIMATED WAVE HEADER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&color=gradient&customColorList=0,2,5,8,11&text=ARTEM%20BIELOV&fontColor=e6edf3&fontSize=54&fontAlignY=32&desc=DevOps%20%C2%B7%20Platform%20%C2%B7%20Full-Stack%20Engineer&descAlignY=52&descSize=18&animation=fadeIn&section=header" alt="header" />

<!-- ANIMATED TYPING HEADLINE -->
<a href="https://artembielov.com/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2600&pause=700&color=35D0BA&center=true&vCenter=true&width=920&height=70&lines=from+git+push+to+reliable+production;automate+the+system.+own+the+outcome.;infrastructure+as+code+%7C+containers+%7C+observability;build+it.+run+it.+improve+it." alt="Animated headline" />
</a>

<p>
  <a href="https://artembielov.com/"><img src="https://img.shields.io/badge/%E2%97%89_STATUS-ONLINE_%2F_BUILDING-35D0BA?style=for-the-badge&labelColor=0D1117" alt="Status" /></a>
  <a href="https://github.com/i6nake9"><img src="https://img.shields.io/badge/%E2%9A%99_MODE-SHIP_%E2%80%A2_OBSERVE_%E2%80%A2_IMPROVE-1F6FEB?style=for-the-badge&labelColor=0D1117" alt="Mode" /></a>
  <a href="mailto:fleshartemka@gmail.com"><img src="https://img.shields.io/badge/%E2%9C%89_OPEN_TO-DEVOPS_%2F_SRE_ROLES-3FB950?style=for-the-badge&labelColor=0D1117" alt="Open to work" /></a>
  <img src="https://komarev.com/ghpvc/?username=i6nake9&label=VISITORS&color=35D0BA&style=for-the-badge" alt="Profile views" />
</p>

<p>
  <a href="https://artembielov.com/"><img src="https://img.shields.io/badge/Website-artembielov.com-35D0BA?style=flat-square&logo=googlechrome&logoColor=white&labelColor=0D1117" alt="Website" /></a>
  <a href="https://dev.to/i6nake9"><img src="https://img.shields.io/badge/dev.to-i6nake9-0D1117?style=flat-square&logo=devdotto&logoColor=white&labelColor=0D1117" alt="dev.to" /></a>
  <a href="https://twitter.com/i6nake9"><img src="https://img.shields.io/badge/X-@i6nake9-0D1117?style=flat-square&logo=x&logoColor=white&labelColor=0D1117" alt="X" /></a>
  <a href="mailto:fleshartemka@gmail.com"><img src="https://img.shields.io/badge/Email-let's_talk-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />

</div>

## `~/identity`

<table>
<tr>
<td width="56%" valign="top">

```yaml
artem@production:~$ cat profile.yaml

name:      Artem Bielov
handle:    "@i6nake9"
location:  Poland / Ukraine
role:      DevOps-minded Platform & Full-Stack Engineer
motto:     "Build it. Run it. Improve it."

mission:
  - turn ideas into deployable products
  - make releases predictable and repeatable
  - replace fragile manual routines with automation
  - build infrastructure that makes business move faster

focus_2026:
  - rust & systems programming
  - kubernetes / cloud-native architecture
  - infrastructure as code
  - observability, security, production ops
```

</td>
<td width="44%" valign="top">

### Signal, not noise

I am a hands-on builder who works across the **full delivery path** — from application code to Linux servers, containers, reverse proxies, databases and production operations.

Running product and e-commerce ventures taught me that a system is only useful when it is **reliable, maintainable, measurable and cost-conscious**.

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3200&pause=900&color=58A6FF&width=420&height=90&lines=%3E+uptime+is+a+feature;%3E+every+manual+step+is+a+future+incident;%3E+logs+today+save+you+at+03%3A00+AM;%3E+measure+first%2C+optimize+second" alt="terminal lines" />

</td>
</tr>
</table>

<details>
<summary><b>▸ Open the production mindset</b></summary>
<br/>

```diff
+ Automate repeatable work — twice done manually means it should be scripted.
+ Version infrastructure and deployment knowledge, not only application code.
+ Design every service as something you may need to debug at 03:00.
+ Measure before optimizing: metrics, logs, traces, then decisions.
+ Security and cost are architecture properties, not afterthoughts.
- "It works on my machine" is not a deployment strategy.
- Snowflake servers configured by hand and remembered by nobody.
```

</details>

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />
</div>

## `~/delivery-pipeline`

<div align="center">

```text
┌──────────┐    ┌──────────────┐    ┌──────────────┐    ┌────────────────┐    ┌─────────────┐
│  WRITE   │ ──▶│   VALIDATE   │ ──▶│   PACKAGE    │ ──▶│    RELEASE     │ ──▶│   OBSERVE   │
│ code/ops │    │ lint/test/CI │    │ Docker image │    │ Linux + Nginx  │    │ logs/health │
└──────────┘    └──────────────┘    └──────────────┘    └────────────────┘    └──────┬──────┘
     ▲                                                                                │
     └───────────────────────── feedback → automate → improve ────────────────────────┘
```

</div>

```mermaid
flowchart LR
    classDef source  fill:#0d1117,stroke:#35D0BA,color:#e6edf3,stroke-width:2px
    classDef process fill:#161b22,stroke:#58A6FF,color:#e6edf3,stroke-width:2px
    classDef live    fill:#13231e,stroke:#3FB950,color:#e6edf3,stroke-width:2px
    classDef watch   fill:#1c1b13,stroke:#D29922,color:#e6edf3,stroke-width:2px

    A["<b>01</b> 💻 Code"]:::source --> B["<b>02</b> 🔀 Git / GitHub"]:::source
    B --> C["<b>03</b> ✅ CI: lint · test · scan"]:::process
    C --> D["<b>04</b> 🐳 Build image"]:::process
    D --> E["<b>05</b> 📦 Registry"]:::process
    E --> F["<b>06</b> ☁️ Deploy: Linux / K8s"]:::live
    F --> G["<b>07</b> 🌐 Nginx · TLS · routing"]:::live
    G --> H["<b>08</b> 🗄️ App + data layer"]:::live
    H --> I["<b>09</b> 🔭 Metrics · logs · alerts"]:::watch
    I -. "telemetry + feedback" .-> A
```

<details>
<summary><b>▸ Reference architecture I like to run</b></summary>
<br/>

```mermaid
flowchart TB
    classDef edge fill:#0d1117,stroke:#35D0BA,color:#e6edf3,stroke-width:2px
    classDef app  fill:#161b22,stroke:#58A6FF,color:#e6edf3,stroke-width:2px
    classDef data fill:#13231e,stroke:#3FB950,color:#e6edf3,stroke-width:2px
    classDef ops  fill:#1c1b13,stroke:#D29922,color:#e6edf3,stroke-width:2px

    U["👤 Users"]:::edge --> CDN["🛡️ CDN / WAF"]:::edge
    CDN --> NG["🌐 Nginx / Traefik<br/>TLS · rate limit"]:::edge

    subgraph RUNTIME["Container runtime"]
      API["⚙️ API services<br/>Node · NestJS · Go · Rust"]:::app
      WRK["🧵 Workers / jobs"]:::app
      WEB["🎨 Next.js frontend"]:::app
    end

    NG --> WEB
    NG --> API
    API --> MQ["📨 Kafka / RabbitMQ"]:::data
    MQ --> WRK

    subgraph STATE["State"]
      PG[("🐘 PostgreSQL")]:::data
      RD[("⚡ Redis cache")]:::data
      OBJ[("🪣 Object storage")]:::data
    end

    API --> PG
    API --> RD
    WRK --> OBJ

    subgraph OPS["Platform"]
      CI["🔁 GitHub Actions"]:::ops
      IAC["🏗️ Terraform · Ansible"]:::ops
      MON["📊 Prometheus · Grafana · Loki"]:::ops
    end

    CI --> RUNTIME
    IAC --> RUNTIME
    RUNTIME --> MON
    STATE --> MON
```

</details>

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />
</div>

## `~/stack --all --grouped`

<div align="center">

### ☁️ &nbsp;Cloud, Platform & Operations

<img src="https://skillicons.dev/icons?i=linux,ubuntu,debian,redhat,arch,bash,powershell,nix,docker,kubernetes,terraform,ansible,githubactions,jenkins,gitlab,nginx,aws,gcp,azure,cloudflare,vercel,netlify,heroku,openshift,prometheus,grafana,git,github,raspberrypi,kali&perline=10&theme=dark" alt="Cloud & Ops" />

<p>
<img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/HAProxy-106DA9?style=flat-square&logo=haproxy&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Consul-F24C53?style=flat-square&logo=consul&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Portainer-13BEF9?style=flat-square&logo=portainer&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/systemd-30363D?style=flat-square&logo=linux&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Cron-30363D?style=flat-square&logo=gnubash&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/UFW%20%2F%20iptables-30363D?style=flat-square&logo=linuxfoundation&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Let's%20Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white&labelColor=0D1117" />
</p>

### 🧠 &nbsp;Languages

<img src="https://skillicons.dev/icons?i=rust,go,ts,js,py,java,kotlin,cs,cpp,c,php,ruby,lua,zig,elixir,scala,haskell,perl,swift,dart,r,solidity,bash,md&perline=12&theme=dark" alt="Languages" />

<p>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/HCL-844FBA?style=flat-square&logo=terraform&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white&labelColor=0D1117" />
</p>

### ⚙️ &nbsp;Backend, Services & APIs

<img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,deno,bun,fastapi,django,flask,spring,dotnet,rails,laravel,symfony,actix,rocket,ktor,graphql,prisma,sequelize,wasm&perline=10&theme=dark" alt="Backend" />

<p>
<img src="https://img.shields.io/badge/gRPC-244B5A?style=flat-square&logo=grpc&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/REST-1F6FEB?style=flat-square&logo=fastapi&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OpenAPI%20%2F%20Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black&labelColor=0D1117" />
<img src="https://img.shields.io/badge/WebSockets-35D0BA?style=flat-square&logo=socketdotio&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OAuth2%20%2F%20JWT-EB5424?style=flat-square&logo=auth0&logoColor=white&labelColor=0D1117" />
</p>

### 🗄️ &nbsp;Data, Storage & Caching

<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,redis,cassandra,dynamodb,elasticsearch,supabase,firebase,planetscale&perline=11&theme=dark" alt="Data" />

<p>
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Memcached-0088CC?style=flat-square&logo=memcached&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white&labelColor=0D1117" />
</p>

### 📨 &nbsp;Message Brokers, Streaming & Async

<img src="https://skillicons.dev/icons?i=kafka,rabbitmq,redis&perline=3&theme=dark" alt="Brokers" />

<p>
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/NATS-27AAE1?style=flat-square&logo=natsdotio&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Apache%20Pulsar-188FFF?style=flat-square&logo=apachepulsar&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/ActiveMQ-D1252A?style=flat-square&logo=apache&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Redis%20Streams-DC382D?style=flat-square&logo=redis&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/BullMQ-E0234E?style=flat-square&logo=nestjs&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Sidekiq-B1003E?style=flat-square&logo=ruby&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white&labelColor=0D1117" />
</p>

### 🔭 &nbsp;Observability, Security & Reliability

<img src="https://skillicons.dev/icons?i=prometheus,grafana,elasticsearch,sentry&perline=4&theme=dark" alt="Observability" />

<p>
<img src="https://img.shields.io/badge/Grafana%20Loki-F46800?style=flat-square&logo=grafana&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Tempo%20%2F%20Jaeger-60D0E4?style=flat-square&logo=jaeger&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/ELK%20Stack-005571?style=flat-square&logo=elasticstack&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Logstash-005571?style=flat-square&logo=logstash&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Uptime%20Kuma-5CDD8B?style=flat-square&logo=uptimekuma&logoColor=black&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Snyk-4C4A73?style=flat-square&logo=snyk&logoColor=white&labelColor=0D1117" />
</p>

### 🎨 &nbsp;Product & Frontend Layer

<img src="https://skillicons.dev/icons?i=nextjs,react,vue,nuxtjs,angular,svelte,solidjs,astro,remix,tailwind,sass,bootstrap,materialui,redux,threejs,htmx,vite,webpack,figma,electron&perline=10&theme=dark" alt="Frontend" />

<p>
<img src="https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Headless%20Commerce-35D0BA?style=flat-square&logo=shopify&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/WordPress%20%2F%20WooCommerce-21759B?style=flat-square&logo=wordpress&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white&labelColor=0D1117" />
</p>

### 🧪 &nbsp;Testing, Quality & Developer Experience

<img src="https://skillicons.dev/icons?i=jest,vitest,cypress,selenium,eslint,prettier,postman,vscode,neovim,vim,idea,cmake,gradle,maven,npm,yarn,pnpm,obsidian,notion,regex&perline=10&theme=dark" alt="Testing & tooling" />

<p>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Mocha-8D6748?style=flat-square&logo=mocha&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/k6%20load%20testing-7D64FF?style=flat-square&logo=k6&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=precommit&logoColor=black&labelColor=0D1117" />
<img src="https://img.shields.io/badge/GNU%20Make-A42E2B?style=flat-square&logo=gnu&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OpenSSH-000000?style=flat-square&logo=openssh&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Starship-DD0B78?style=flat-square&logo=starship&logoColor=white&labelColor=0D1117" />
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />

</div>

## `~/now --progress`

<div align="center">

```text
╭───────────────────────────── CURRENT QUESTS ──────────────────────────────╮
│                                                                           │
│  Rust & systems programming              [████████░░]  80%                │
│  Kubernetes / cloud-native architecture  [███████░░░]  70%                │
│  Infrastructure as Code (TF + Ansible)   [███████░░░]  70%                │
│  Observability & SRE practices           [████████░░]  75%                │
│  Platform security & hardening           [██████░░░░]  60%                │
│  Cost-aware cloud architecture           [█████░░░░░]  55%                │
│                                                                           │
╰───────────────────────────────────────────────────────────────────────────╯
```

</div>

| Beacon | Current trajectory |
|:--|:--|
| `⚡ BUILD` | E-commerce and web products with an automation-first architecture |
| `🐳 OPERATE` | Containerized services, Linux deployments, reverse proxies, databases |
| `🦀 LEARN` | Rust, systems / embedded engineering, platform engineering practices |
| `🔭 EXPLORE` | IaC, Kubernetes, observability, resilient cloud-native delivery |
| `🤝 OPEN TO` | DevOps / SRE / Platform Engineer roles · remote or Poland-based |

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />
</div>

## `~/telemetry`

<div align="center">

<a href="https://github.com/i6nake9">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=i6nake9&show_icons=true&theme=transparent&hide_border=true&title_color=35D0BA&icon_color=58A6FF&text_color=C9D1D9&ring_color=35D0BA&include_all_commits=true&count_private=true" alt="GitHub statistics" />
</a>
<a href="https://github.com/i6nake9">
  <img height="180" src="https://streak-stats.demolab.com?user=i6nake9&theme=transparent&hide_border=true&ring=35D0BA&fire=35D0BA&currStreakLabel=35D0BA&sideLabels=C9D1D9&dates=8B949E&stroke=30363D" alt="GitHub contribution streak" />
</a>

<br/>

<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=i6nake9&layout=compact&langs_count=12&theme=transparent&hide_border=true&title_color=35D0BA&text_color=C9D1D9" alt="Top languages" />

<br/><br/>

<!-- ANIMATED CONTRIBUTION ACTIVITY GRAPH -->
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=i6nake9&bg_color=0D1117&color=35D0BA&line=35D0BA&point=58A6FF&area=true&area_color=1F6FEB&title_color=35D0BA&hide_border=true" alt="Contribution activity graph" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=i6nake9&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6" alt="Trophies" />

</div>

<details>
<summary><b>▸ Deep telemetry (extra cards)</b></summary>
<br/>
<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=i6nake9&theme=github_dark" height="180" alt="Repos per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=i6nake9&theme=github_dark" height="180" alt="Most commit language" />
<br/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=i6nake9&theme=github_dark&utcOffset=2" height="180" alt="Productive time" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=i6nake9&theme=github_dark" height="180" alt="Profile stats" />

</div>
</details>

<!--
  ANIMATED CONTRIBUTION SNAKE
  Works after you add the workflow file: .github/workflows/snake.yml
  (see snake.yml shipped together with this README)
  Then uncomment the block below.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/i6nake9/i6nake9/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/i6nake9/i6nake9/output/github-contribution-grid-snake.svg" />
    <img alt="Animated contribution snake" src="https://raw.githubusercontent.com/i6nake9/i6nake9/output/github-contribution-grid-snake.svg" />
  </picture>
</div>
-->

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,5,8,11&height=3&section=header" alt="" />
</div>

## `~/connect`

<div align="center">

<a href="https://artembielov.com/"><img src="https://img.shields.io/badge/Website-artembielov.com-35D0BA?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0D1117" alt="Personal website" /></a>
<a href="https://dev.to/i6nake9"><img src="https://img.shields.io/badge/dev.to-i6nake9-0D1117?style=for-the-badge&logo=devdotto&logoColor=white&labelColor=0D1117" alt="Dev.to" /></a>
<a href="https://twitter.com/i6nake9"><img src="https://img.shields.io/badge/X-@i6nake9-0D1117?style=for-the-badge&logo=x&logoColor=white&labelColor=0D1117" alt="X" /></a>
<a href="mailto:fleshartemka@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=3400&pause=1000&color=35D0BA&center=true&vCenter=true&width=760&height=45&lines=If+opportunities+do+not+knock%2C+build+a+door;then+automate+the+deployment." alt="closing line" />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&color=gradient&customColorList=0,2,5,8,11&section=footer&animation=fadeIn" alt="footer" />

<code>system.status = "BUILDING · SHIPPING · AUTOMATING"</code>

</div>
