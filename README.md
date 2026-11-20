<picture>
  <source media="(max-width: 700px) and (prefers-color-scheme: dark)" srcset="assets/header-mobile-dark.svg">
  <source media="(max-width: 700px)" srcset="assets/header-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Ankit Katiyar · Applied AI Engineer at Vaisala · automating the whole software pipeline with AI agents, 24×7">
</picture>

<p align="center">
  <a href="https://ankitkatiyar567.github.io"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/therealsignet"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@theRealSignet"><img src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="mailto:ankit.katiyar91@gmail.com"><img src="https://img.shields.io/badge/Email-D97757?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=ankitkatiyar567&style=flat-square&color=8b5cf6&label=views" alt="Profile views" />
</p>

## 🛠️ What I build

- **🏭 Software factories**<br/>Teams of agents (product owner, architect, developer, QA, reviewer) take a requirement and ship a merged pull request end to end, 24×7 on a local cluster and AWS.
- **🔍 Code‑review bot**<br/>AI review on every pull request across the organisation, with specialist lenses for bugs, security and design, and the same review as a CLI before you push.
- **🔁 Full pipeline automation**<br/>Requirement, plan, design, code, tests, review, release and maintenance: agents do the steps, people approve them.
- **🧠 Claude skills**<br/>Packaged know‑how that agents load when they need it: factory runbooks, review checklists, release steps.
- **🔌 Plugins**<br/>Claude Code plugins with commands, hooks and sub‑agents that bring a team's whole workflow into the terminal.
- **🛰️ MCP servers**<br/>Safe tools and data for agents: repositories, tickets, docs and code knowledge graphs, so they read only what matters.

## 🧭 How I work

**🤖 Agents do the work** · **👀 People decide** · **✅ Green CI or no merge** · **🏠 Own cloud or local**

<sub>Agents plan, code, test and review, and I design the system they work in. Every change gets an AI review and a person's yes before it ships; open blocking findings stop the merge. AI runs in our own AWS account or on local models, so code and data stay with us.</sub>

<details>
<summary><b>How a change flows through the pipeline</b></summary>
<br/>

```mermaid
flowchart LR
  R([📋 Requirement]) --> P[🗺️ Plan] --> D[🏛️ Design] --> C[⌨️ Code] --> T[🧪 Test] --> V[🔍 Review] --> S([🚀 Deploy]) --> M[🔧 Maintain]
  V -. findings .-> C
  M -. new work .-> R
  K[(🧠 Skills · 🔌 plugins · 🛰️ MCP)] -.- P & D & C & T & V
  classDef n fill:#15192b,stroke:#8b5cf6,color:#eef1f8,rx:8,ry:8;
  classDef k fill:#0b2530,stroke:#22d3ee,color:#eef1f8;
  class R,P,D,C,T,V,S,M n;
  class K k;
```

</details>

## 🧪 Projects

### ⭐ [Ihaaya](https://ankitkatiyar567.github.io/ihaya/) · built at home

*Shine a little brighter every day.*

<p align="center">
  <a href="https://ankitkatiyar567.github.io/ihaya/"><img src="https://raw.githubusercontent.com/ankitkatiyar567/ihaya/main/screenshots/1-landing.png?v=3" width="145" alt="Logo and parent PIN" /></a>
  <a href="https://ankitkatiyar567.github.io/ihaya/"><img src="https://raw.githubusercontent.com/ankitkatiyar567/ihaya/main/screenshots/2-chart.png?v=3" width="145" alt="The day's picture tasks" /></a>
  <a href="https://ankitkatiyar567.github.io/ihaya/"><img src="https://raw.githubusercontent.com/ankitkatiyar567/ihaya/main/screenshots/3-report.png?v=3" width="145" alt="Friday report" /></a>
  <a href="https://ankitkatiyar567.github.io/ihaya/"><img src="https://raw.githubusercontent.com/ankitkatiyar567/ihaya/main/screenshots/4-game-and-story.png?v=3" width="145" alt="Daily game and bedtime story" /></a>
</p>

A picture star chart I built for my 5‑year‑old daughter. Every evening she rates her own day with ⭐ or ❌ on picture tasks (sleep, TV time, food, tidying up, kindness, how often she cried), a good day opens a 3‑minute mini game, and every night ends with a 7–10 minute bedtime story. Free, no sign‑up, works as a phone app and keeps the data on the phone.

**Why:** at this age kids get angry and stubborn, and scolding rarely works. Rating herself teaches her to be honest about her own day, the stars and the game turn good behaviour into small wins she can see, and the Friday report celebrates a good week or gently shows what to practise, never with punishment. A clear routine she looks forward to does the disciplining for us.

<a href="https://ankitkatiyar567.github.io/ihaya/"><img src="https://img.shields.io/badge/Open_the_app-8B5CF6?style=flat-square&logo=pwa&logoColor=white" alt="Open the app" /></a>
<a href="https://github.com/ankitkatiyar567/ihaya"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source code" /></a>

#### More

- **📚 [Kids Story Buddy](https://github.com/ankitkatiyar567/kids-story-buddy)**<br/>A voice‑driven choose‑your‑own‑adventure story app for kids, in English, Hindi and Finnish.
- **🌐 [Portfolio](https://ankitkatiyar567.github.io)**<br/>My AI‑themed CV and portfolio: projects, writing and the way I work with agents.

## 🧰 Stack

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,nestjs,ts,nodejs,py,aws,terraform,docker,kubernetes,githubactions,postgres,mongodb,git&theme=dark&perline=7" alt="Tech stack" />
</p>

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Claude_Skills-8B5CF6?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Skills" />
  <img src="https://img.shields.io/badge/Plugins-8B5CF6?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code plugins" />
  <img src="https://img.shields.io/badge/MCP-0891B2?style=flat-square&logo=anthropic&logoColor=white" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Multi--agent_systems-0891B2?style=flat-square&logo=ray&logoColor=white" alt="Multi-agent systems" />
  <img src="https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="Amazon Bedrock" />
  <img src="https://img.shields.io/badge/Local_LLMs-059669?style=flat-square&logo=apple&logoColor=white" alt="Local LLMs" />
</p>

## 👤 About

- 🤖 Applied AI Engineer at **Vaisala**, automating the software pipeline end to end with multi‑agent systems
- 🏗️ **13+ years** of Java 17, Spring Boot and NestJS on AWS and Kubernetes, in renewable energy, smart metering and logistics
- ✍️ I write about practical, tool‑centric AI on [Medium @theRealSignet](https://medium.com/@theRealSignet)

## ✍️ Latest writing

- [AI's Next Phase Won't Be Bigger Models — It Will Be Smaller, Specialized, and Tool-Centric](https://medium.com/@theRealSignet)
- [Built a Free AI Code Review Tool for Bitbucket Server Using Just a Markdown File](https://medium.com/@theRealSignet)
- [I Stopped Using AI as a Tool. I Started Architecting With It.](https://medium.com/@theRealSignet)

<p align="center"><sub>Built with agents · reviewed by people</sub></p>
