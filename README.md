# Hi, I'm Edmund Gray 👋

**Applied AI Builder · Agents in Production · Federal Delivery · Active DoD Secret Clearance**

I design and ship full-stack AI systems end to end, from concept to deployed cloud apps that real people use. Behind that: 20+ years across AT&T, Google, and DoD federal contracting, including 17 months on a DoD procurement platform under Section 508.

I build agents that do real work, not demos: LLM reasoning wired into live data, a secure serverless pattern that keeps API keys off the client, evaluation harnesses that gate release, and guards enforced in code rather than in the prompt.

---

## 🔷 Flagship: Grayrender

### [**Grayrender: AI Marketing Audit and Content Suite →**](https://github.com/howrealizdat/grayrender)

**An AI marketing audit that renders the page before it judges it.** [Live demo](https://grayrender.netlify.app) (passcode by request)

Twelve tools, a per-business workspace, and a live meeting copilot, built around one flagship: a full-site audit that drives a real headless browser over every key page, measures the layout, looks at a screenshot, and only then writes the report.

**What makes it different**

- **It cannot claim what it did not observe.** Most SEO tools read raw HTML and guess. Grayrender captures the post-JavaScript DOM, a full-page screenshot, and the measured bounding box of every heading, button, link, and form control, so it knows what is actually above the fold. That one constraint drove the whole architecture.
- **Truthfulness is enforced in code, not in the prompt.** A model ignores a prompt rule on roughly 10 to 30 percent of runs. So anything that must never appear is blocked after generation: grounding, prompt rules, then code guards that drop any fix asserting a fabricated value.
- **Tested like production.** `npm test` runs **569 assertions across four suites** covering auth (an unauthenticated caller can never reach a paid API), audit guards, report rendering, and workspace integrity.
- **Measured, not hand-waved.** A five-page audit runs in about 95 seconds at roughly **$0.095 per run**.
- **Secure by default.** Everything runs behind Netlify serverless functions. Zero API key exposure, server-side passcode enforcement that fails closed.

`Claude API` · `Netlify Functions` · `headless Chrome (Browserless)` · `JavaScript` · `serverless`

---

## 🚀 More shipped work

| Project | What it is | Stack |
|---|---|---|
| ⚡ [**Draft Co-Pilot**](https://github.com/howrealizdat/draft-co-pilot) | Live, league-scoring-aware draft assistant that runs inside the ESPN draft room. Values every player by value over replacement under that league's exact rules and re-ranks on every pick. Tuned across 30+ versions, each validated against ESPN's own post-draft grades. | Chrome Extension (MV3) · vanilla JS · ESPN API |
| 🎯 [**DFS Lineup Optimizer**](https://github.com/howrealizdat/dfs-lineup-optimizer) | Constraint optimization builds salary-cap lineups, then a Claude reasoning layer explains, rates, and suggests swaps. Explainable AI over a real solver. | Python · Google OR-Tools · Claude API |
| 🏝️ [**Panama Vista Realty**](https://github.com/howrealizdat/panama-vista-realty) | Full-stack AI real estate concierge: live listings plus a Claude agent grounded in Panama property law, foreign-buyer rules, and visa programs. Same secure serverless pattern, different domain. | JS · Claude API · Netlify Functions |
| 🏁 [**We On The Lodge**](https://github.com/howrealizdat/we-on-the-lodge) | Solo-built pseudo-3D racing game on Detroit's Lodge Freeway. Extended an open-source engine through a non-invasive overlay that held core edits to three lines, then diagnosed and fixed a fatal balance flaw by instrumenting the source. | HTML5 Canvas · JS · AI art/audio pipeline |

Also: **five published ChatGPT-store GPTs** built on RAG knowledge bases and OAuth-gated Actions, three past 300 to 1,000+ conversations.

---

## 🛠️ Skills

**Applied AI & Agents** — Anthropic Claude API and SDK · agent and system-prompt design · tool and function calling · Model Context Protocol (MCP) · RAG · prompt and context engineering · LLM evaluation, guardrails, and failure-mode analysis

**Agentic Dev Tooling** — Claude Code · OpenAI Codex · Cursor · GitHub Copilot

**Development** — Python · JavaScript · HTML/CSS · Netlify serverless functions · Google OR-Tools · Chrome Extensions (MV3) · REST APIs · automated test suites

**Data & BI** — Google Analytics (GA4) · Google Tag Manager · BigQuery · SQL · Tableau · Power BI

**Delivery & Compliance** — Agile · JIRA · Section 508 accessibility · WCAG 2.x · federal content lifecycle

---

## 📜 Credentials

**Anthropic:** [Building with the Claude API](https://verify.skilljar.com/c/hptasgs5gk8k) · [Introduction to Model Context Protocol](https://verify.skilljar.com/c/eoy24265pqak) · [Introduction to Agent Skills](https://verify.skilljar.com/c/qax7a29mob9d) · [Claude Code in Action](https://verify.skilljar.com/c/3pcfs8u4nowt)

**Certified DHS Trusted Tester for Web (Section 508)**, 2026, scored 88/100 · **Active DoD Secret Clearance**, 8(a) eligible · U.S. Citizen, Public Trust eligible · CompTIA Security+ · AWS Educate Generative AI & ML Foundations · Google Data Analytics · Certified ScrumMaster · FAA Part 107

---

📫 **EdmundGrayworks@gmail.com** · [LinkedIn](https://www.linkedin.com/in/edmundgraylinked) · [Portfolio Deck](https://docs.google.com/presentation/d/1MX404b0LTaGQPXRP864tZmg5mBgJY2p8/edit?usp=sharing&ouid=116410740894220247898&rtpof=true&sd=true)
