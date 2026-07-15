<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,50:4c1d95,100:6d28d9&height=200&section=header&text=Dylan%20Carter&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineer%20%7C%20AI%20Systems%20%7C%20Full%20Stack&descAlignY=55&descAlign=50" />

<a href="https://github.com/dylancarter16">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&lines=Honours+Computer+Science+%40+Waterloo;Building+AI-Native+Products;Full+Stack+Engineer;Automation+%26+Data+Pipelines" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/University%20of%20Waterloo-Honours%20Computer%20Science-4C1D95?style=for-the-badge&labelColor=1E1B4B" />
<img src="https://img.shields.io/badge/Class%20of-2030-6D28D9?style=for-the-badge&labelColor=1E1B4B" />
<img src="https://img.shields.io/badge/Toronto-Ontario%2C%20Canada-7C3AED?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=1E1B4B" />

<br/><br/>

<a href="https://prospect-tau-three.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-Live%20Project-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1E1B4B" />
</a>
<a href="https://www.linkedin.com/in/dylan-carter-55411a3a2">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1E1B4B" />
</a>
<a href="mailto:D7Carter@uwaterloo.ca">
  <img src="https://img.shields.io/badge/Email-Reach%20Out-7C3AED?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1E1B4B" />
</a>
<a href="https://github.com/dylancarter16">
  <img src="https://img.shields.io/badge/GitHub-Follow-4C1D95?style=for-the-badge&logo=github&logoColor=white&labelColor=1E1B4B" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=dylancarter16&label=Profile%20Views&color=8B5CF6&style=flat-square" />
<img src="https://img.shields.io/github/followers/dylancarter16?label=Followers&style=flat-square&color=8B5CF6&labelColor=1E1B4B" />
<img src="https://img.shields.io/github/stars/dylancarter16?label=Total%20Stars&style=flat-square&color=8B5CF6&labelColor=1E1B4B" />

</div>

---

## About

I'm an Honours Computer Science student at the University of Waterloo who builds production systems, not demos. My work sits at the intersection of **software engineering**, **applied AI**, and **automation** — designing full-stack architectures, shipping LLM-powered features that solve real problems, and eliminating manual workflows at enterprise scale.

I care about the parts of engineering that don't show up in a screenshot: schema design, security boundaries, fallback strategies, and the discipline of shipping something people actually use. Every project below is deployed and running in production.

**Currently:** IT Data & Analytics Intern at Redpath Sugar, building AI automation agents and Python data pipelines for a 130-year-old manufacturing enterprise.

### Open To

```
Software Engineering Internships   ·   AI / ML Engineering Internships
Full Stack Development             ·   Data & Automation Engineering
Winter 2027 Co-op Terms (Jan – Apr)
```

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,java,c&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,postgres,supabase,sqlite&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=vercel,githubactions,git,github,vscode,linux&theme=dark" />

</div>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|:---|:---:|:---|
| **LLM Application Engineering** | Advanced | Production integrations with Anthropic Claude API and OpenAI API; server-side-only architecture; structured JSON output enforcement; 5 shipped AI features across production apps |
| **Agentic Systems** | Advanced | LangChain ReAct agents for natural-language database querying; LangGraph orchestration; Microsoft Copilot Studio and Copilot Agent Builder agents with custom Python backends |
| **Prompt Engineering** | Advanced | Schema-constrained extraction, reusable prompt libraries, anomaly-detection prompting, tailored generation pipelines |
| **Data Pipeline Architecture** | Advanced | Multi-tier fallback chains (REST → scraper → AI search); delta detection; automated refresh via CI/CD; full source auditability |
| **Data Validation & Integrity** | Proficient | Pydantic schema enforcement; LLM-assisted anomaly flagging; timestamped provenance tracking |
| **Document Intelligence** | Proficient | PDF extraction pipelines (PyPDF2), resume parsing, keyword gap analysis, semantic relevance matching |
| **Workflow Automation** | Advanced | Power Automate orchestration, Microsoft Graph API integration, VBA/COM automation, SharePoint-backed delta pipelines |

---

## Featured Projects

<details open>
<summary><b>Prospect</b> — AI-Powered Co-op Application Tracker</summary>

<br/>

A full-stack platform that helps students manage internship and co-op applications end to end — with AI doing the work that actually matters: parsing job descriptions, scoring resumes against them, and generating interview prep.

| | |
|:---|:---|
| **Stack** | Next.js 14 · TypeScript · PostgreSQL · Supabase · Tailwind CSS · Anthropic Claude API · Vercel |
| **Scale** | 7-table relational schema · 4,000+ lines of TypeScript · 5 AI-powered feature routes |
| **Performance** | Server Actions for CRUD · Postgres triggers for automatic status-history logging · live countdown widgets querying a relational calendar table |
| **Security** | Row-level security enforced on every table · API keys server-side only · auth-gated AI routes · input length validation · per-user rate limiting |
| **Impact** | Automates the entire co-op application lifecycle: JD parsing, resume-to-JD matching, keyword gap analysis, interview question generation, and drag-and-drop ranking |
| **Repository** | [github.com/dylancarter16/prospect](https://github.com/dylancarter16/prospect) · [Live Demo](https://prospect-tau-three.vercel.app) |

Designed the complete architecture from schema to deployment. The AI layer runs entirely through Next.js API routes with server-side-only key handling — every Claude call is authenticated, length-capped, and rate-limited before it reaches the model. Waterloo-specific features (cycle filtering, WaterlooWorks ranking, match-date countdowns) activate automatically via email domain detection, while the core product stays school-agnostic.

</details>

<details>
<summary><b>Vision One Million</b> — Autonomous Government Data Pipeline</summary>

<br/>

An end-to-end system that automates Waterloo Region's population growth readiness scorecard — a public policy instrument tracking regional preparedness across housing, transportation, healthcare, employment, and placemaking.

| | |
|:---|:---|
| **Stack** | Python · LangChain · LangGraph · Streamlit · BeautifulSoup · PyPDF2 · Pydantic · SQLite · GitHub Actions · OpenAI API · Tavily |
| **Scale** | 5+ government data sources · 5 policy domains · fully autonomous weekly refresh cycle |
| **Performance** | Three-tier fallback chain: REST APIs → BeautifulSoup scrapers → Tavily AI search · zero-human-involvement CI/CD refresh |
| **Security** | Pydantic schema validation on all ingested data · GPT-4o-mini anomaly detection pre-persistence · timestamped source auditability |
| **Impact** | Eliminated an estimated **160 hours/year** of manual research · presented to **100+** attendees · live public dashboard |
| **Repository** | [github.com/dylancarter16/vision-one-million](https://github.com/dylancarter16/vision-one-million) · [Live Demo](https://vision-one-million.streamlit.app) |

Led a 3-person team at the FCI × LangChain Building the Future Cities Hackathon. The core engineering challenge was reliability: government data sources fail unpredictably, so the pipeline degrades gracefully through three independent acquisition strategies before surfacing a gap. A LangChain ReAct agent sits on top of the SQLite store, allowing the entire dataset to be queried in plain English.

</details>

<details>
<summary><b>ASR/FCC Timeline Generator</b> — Enterprise PowerPoint Automation</summary>

<br/>

A VBA/COM automation tool that programmatically constructs brand-compliant PowerPoint timeline decks directly from structured Excel project data.

| | |
|:---|:---|
| **Stack** | VBA · COM Automation · Excel Object Model · PowerPoint Object Model |
| **Scale** | Deployed to 30+ PMO employees organization-wide · 3 corporate theme variants |
| **Performance** | Generates complete brand-compliant decks in seconds from raw structured data |
| **Security** | Runs entirely within the corporate M365 tenant · no external data transmission |
| **Impact** | Saves **~1 hour of manual work per use** across the entire PMO organization |
| **Repository** | Proprietary — Redpath Sugar Ltd. |

Built during my first co-op term. The interesting constraint was brand compliance: every generated deck had to be pixel-consistent with corporate templates across three themes, which meant driving the PowerPoint object model directly rather than templating. Cut a recurring, error-prone manual process down to a single click.

</details>

---

## Experience

### **IT Data & Analytics Intern** · Redpath Sugar Ltd.
**May 2026 – August 2026** · Toronto, ON

Building automation infrastructure and AI-enabled workflows for Canada's largest sugar refinery — a 130-year-old manufacturing enterprise undergoing digital transformation.

**Scope of Work**
- Engineered a VBA/COM automation tool generating brand-compliant PowerPoint timelines from structured Excel data, deployed to 30+ PMO employees across 3 corporate themes
- Designed and built a Python data pipeline (pandas, Microsoft Graph API) implementing delta detection against a SharePoint-backed data store, fully automating SAP SuccessFactors release monitoring
- Developed AI automation agents in Microsoft Copilot Studio and Copilot Agent Builder with custom Python backends to identify and eliminate recurring manual workflows
- Configured and maintained endpoint infrastructure including laptops, desktops, and Honeywell Thor vehicle-mounted computers across operational teams

`Python` `pandas` `VBA` `Microsoft Graph API` `Power Automate` `Copilot Studio` `Copilot Agent Builder` `SharePoint` `SAP`

<br/>

### **Gymnastics Coach** · NCCP Competition-One Certified
**2022 – 2025** · Toronto, ON · 1,000+ Coaching Hours

Developed athletes from recreational beginner through Team Ontario competitive level across 1,000+ on-floor hours.

**Scope of Work**
- Designed individualized training progressions under standardized NCCP curriculum, scaling instruction across widely varying skill levels
- Maintained safe, inclusive participation for athletes of diverse abilities through curriculum adaptation
- Communicated proactively with athletes, parents, and coaching peers across a high-stakes competitive program

`Leadership` `Curriculum Design` `Stakeholder Communication` `Mentorship`

---

## Achievements

<div align="center">

| Recognition | Details |
|:---|:---|
| **FCI × LangChain Hackathon** | Led a 3-person team; presented Vision One Million to 100+ attendees (March 2026) |
| **160 Hours/Year Automated** | Eliminated a full year's manual research workload for a regional public policy instrument |
| **Enterprise Deployment at 19** | Shipped automation tooling to 30+ employees in a 130-year-old manufacturing enterprise during first co-op |
| **Euclid Mathematics Contest** | University of Waterloo CEMC · Grade 12 |
| **Canadian Computing Competition** | CCC Senior Division · Grade 12 |
| **Fermat Mathematics Contest** | University of Waterloo CEMC · Grade 11 |
| **96% Grade 12 Average** | Harbord Collegiate Institute, Toronto |

</div>

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=dylancarter16&show_icons=true&theme=react&title_color=8B5CF6&icon_color=A78BFA&text_color=c9d1d9&bg_color=0d1117&border_color=4C1D95&include_all_commits=true&count_private=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dylancarter16&layout=compact&theme=react&title_color=8B5CF6&text_color=c9d1d9&bg_color=0d1117&border_color=4C1D95&langs_count=8" />

<br/>

<img src="https://streak-stats.demolab.com?user=dylancarter16&theme=react&background=0d1117&border=4C1D95&stroke=4C1D95&ring=8B5CF6&fire=A78BFA&currStreakLabel=8B5CF6&sideLabels=c9d1d9&dates=8b949e" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=dylancarter16&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

</div>

---

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=dylancarter16&bg_color=0d1117&color=8B5CF6&line=A78BFA&point=ffffff&area=true&hide_border=true" />

</div>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/dylancarter16/dylancarter16/output/snake.svg" alt="Snake animation" />

</div>

---

## Current Focus

```yaml
learning:
  - React & Next.js architecture patterns
  - PostgreSQL performance & schema design
  - Distributed systems fundamentals
  - CS 245 / CS 246 — Waterloo core sequence

building:
  - Prospect — scaling to real users across Waterloo
  - Analytics engine: application funnel & conversion insights
  - Anonymous community offer-data aggregation layer

exploring:
  - Agentic AI architectures & tool-use orchestration
  - Model Context Protocol (MCP)
  - Retrieval-augmented generation at production scale
  - Enterprise AI adoption patterns

open_to:
  - Software Engineering Internships
  - AI / ML Engineering Internships
  - Full Stack & Data Engineering Roles
  - Winter 2027 Co-op (January – April)
```

---

## Connect

<div align="center">

<a href="mailto:D7Carter@uwaterloo.ca">
  <img src="https://img.shields.io/badge/Gmail-D7Carter%40uwaterloo.ca-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1E1B4B" />
</a>
<a href="https://www.linkedin.com/in/dylan-carter-55411a3a2">
  <img src="https://img.shields.io/badge/LinkedIn-Dylan%20Carter-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1E1B4B" />
</a>
<a href="https://github.com/dylancarter16">
  <img src="https://img.shields.io/badge/GitHub-dylancarter16-4C1D95?style=for-the-badge&logo=github&logoColor=white&labelColor=1E1B4B" />
</a>
<a href="https://prospect-tau-three.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-Prospect-7C3AED?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1E1B4B" />
</a>

</div>

---

<div align="center">

### *"Ship the thing. Then make it good."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6d28d9,50:4c1d95,100:1e1b4b&height=120&section=footer" />

</div>
