<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&center=true&vCenter=true&width=720&height=60&duration=3500&pause=800&lines=Hi%2C+I'm+Ashley+Sum+%F0%9F%91%8B;I+build+software+and+prove+it+works.;SWE+%C2%B7+AI+%C2%B7+Forward-Deployed+Eng." alt="Hi, I'm Ashley Sum. I build software and prove it works. SWE, AI and forward-deployed engineering." />
</h1>

<h3 align="center">CS @ San Francisco State (GPA 4.00) · Software engineer who ships, measures and proves it</h3>

<p align="center">Open to <b>Summer 2027</b> internships in software engineering, AI engineering and forward-deployed engineering.</p>

<div align="center">
  <a href="mailto:ashleysumtzele04@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=red" alt="Email" /></a>
  <a href="https://linkedin.com/in/ashley-sum" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://ashleytzelesum.com" target="_blank"><img src="https://img.shields.io/badge/Portfolio-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://gatorpath.fly.dev" target="_blank"><img src="https://img.shields.io/badge/Live-GatorPath-F59E0B?style=for-the-badge&logo=flydotio&logoColor=white" alt="GatorPath live" /></a>
  <br/>
  <a href="https://github.com/ashleytzele/ashleytzele/actions/workflows/links.yml"><img src="https://github.com/ashleytzele/ashleytzele/actions/workflows/links.yml/badge.svg" alt="Every link on this page, checked weekly" /></a>
</div>

<hr/>

- 🔭 **Now:** building [GatorPath](https://gatorpath.fly.dev), an AI degree planner for SF State students where the LLM proposes and a deterministic verifier decides.
- 🛣️ **Last summer:** Software Development Engineer Intern at OSPIT Mobility (Selangor, Malaysia): kept highway assets in sync across Odoo, traffic-management APIs and OpenNMS, and built fault correlation that cut outage tickets by about 90%.
- 📏 **How I work:** measure first. Evals, test suites and real numbers before claims. Even this page checks its own links every week.
- 🏊 **Off-screen:** former competitive swimmer (Selangor and Malaysia age-group), Alcatraz swim finisher, aquatics student lead at SF State.

<h2 align="center">Featured projects</h2>

| Project | What it is | Evidence |
|---|---|---|
| [**GatorPath**](https://github.com/ashleytzele/gatorpath) · [live](https://gatorpath.fly.dev) | MCP server (18 tools) + React/TypeScript site with a Claude chat; 108 majors encoded as page-cited YAML | **0** hallucinated course codes across a 47-question eval on 3 AI clients · **−53%** tokens per answer · **956** tests |
| [**Quorum**](https://github.com/ashleytzele/Quorum) | Meeting transcripts and team notes → templated minutes (Python, Flask, GPT-4o-mini, Supabase) | Whisper large-v3-turbo cut transcription **5–8×** · SSRF guard on link fetching |
| [**Scoutmini**](https://github.com/ashleytzele/scoutmini) | F1 research CLI: the model only sees data the tools fetched, and cites it | **73** tests, every external call fixtured, runs offline |
| [**SplitWise**](https://github.com/ashleytzele/SplitWise-Swim) | Swim performance analytics: splits, velocity, stroke rate (Flask, SQLite, Chart.js) | Shipped on Render with login and comparison dashboards |

<details>
<summary><b>How GatorPath keeps the AI honest</b></summary>
<br/>

```mermaid
flowchart LR
    S["Student goal + degree audit<br/>(name and ID dropped on import)"] --> A["Claude proposes a plan"]
    A -->|"MCP tool call"| R[("Bulletin rules<br/>108 majors, page-cited YAML")]
    R -->|"facts + page citations"| A
    A --> V{"check_plan<br/>verifier"}
    V -->|"passes"| P["Plan shown to student"]
    V -->|"fails"| X["Refused, or kept and<br/>marked failing if the student insists"]
```

The model never answers from memory. Every course code, prerequisite and requirement comes from a tool that reads the official Bulletin, and every plan, AI-written or not, has to pass the same deterministic check.

</details>

<h2 align="center">Tools I build with</h2>

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,java,cpp,html,css,react,nodejs,express" alt="Python, TypeScript, JavaScript, Java, C++, HTML, CSS, React, Node.js, Express" /><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,flask,sqlite,mongodb,supabase,docker,githubactions,git,linux" alt="FastAPI, Flask, SQLite, MongoDB, Supabase, Docker, GitHub Actions, Git, Linux" />
</div>

<h2 align="center">Contributions</h2>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="profile-3d-contrib/profile-night-green.svg" />
    <img src="profile-3d-contrib/profile-green-animate.svg" alt="3D view of my GitHub contributions" />
  </picture>
  <br/><br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ashleytzele/ashleytzele/output/github-contribution-grid-snake-dark.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/ashleytzele/ashleytzele/output/github-contribution-grid-snake.svg" />
  </picture>
</div>
