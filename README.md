# Matt Spaulding

**AI Product Engineer & Technical Leader**

Tampa, Florida. Founding AI Technical Lead at Calibrate Group.

I design and ship production AI systems: agent orchestration, retrieval, tool calling, and evaluation
loops. 15+ years building software that ships and stays stable, hands-on across architecture and
delivery. I work at the intersection of product decisions and
engineering execution, and I sit with the customers who use what gets built.

[mattspaulding.org](https://www.mattspaulding.org) · [LinkedIn](https://linkedin.com/in/spauldingmatthew) · [GitHub](https://github.com/mattspaulding)

---

## Featured projects

### [Actuary402](https://github.com/mattspaulding/actuary)

**The paying watchdog: the agent economy, measured.** (Jul 2026)

An autonomous probe fleet that buys from services on Circle's Agent Marketplace with real USDC
nanopayments and has Gemini grade whatever comes back. Other agents can then buy the resulting trust
score for $0.001 a lookup. Billed as "Moody's plus Pingdom for machine commerce": a
reputation layer that funds its own observations.

- Every observation is a real paid transaction.
- x402 payments with Circle Gateway batching. No accounts, no API keys.
- Gemini grades each paid response, and the graded history becomes a trust score other agents can buy.
- Runs on the Circle Agent Stack and Google Cloud Run. Submitted to the Build with Gemini XPRIZE.
- TypeScript.

### [Mender](https://github.com/mattspaulding/mender-agent)

**Self-healing for production agents.** Built for the Google Cloud Rapid Agent Hackathon, Arize track
(May to June 2026).

Every 15 minutes Mender reads another agent's traces through the Arize Phoenix MCP server, clusters
failures, hypothesizes a root cause, generates a focused eval set, drafts a prompt patch, re-runs the
evals against the patch, and, if it measurably improves, posts a structured incident card to Slack
for one-click human approval. A human still ships the fix. It also reads its own traces each cycle
and tunes itself, including how many evals to generate and when to ask for help.

**Verified result:** it caught a real regression, where an ambiguous source currency silently
defaulted to USD. On 10 generated eval cases the patched version passed 10/10, up from 4/10.

**Stack:** Google ADK (Python), Gemini 3 on Vertex AI, Arize Phoenix + Phoenix MCP, Slack Block Kit,
Cloud Run, Cloud Scheduler, Firestore.

[Live demo](https://mender-thj3gr276a-uc.a.run.app)

---

## Calibrate Group

**Founding AI Technical Lead**, Jun 2026 to present

AI consulting firm serving owner-operated businesses. I work forward deployed with clients across
several industries, scoping each operation and building vertical AI solutions to fit it.

---

## Beesla

**Founder & AI Product Lead**, Apr 2025 to present · [beesla.com](https://beesla.com)

AI-native platform that converts natural language into structured workflows: agent orchestration,
retrieval, tool calling, and evaluation loops on Anthropic Claude. Reached **1M+ impressions** across
search engines and AI assistants and **80K+ unique users**.

TypeScript, Node, React, Next.js, Docker, Vercel, Supabase (PostgreSQL), Anthropic Claude, vector search.

---

## Shipped products

Independent studio work through Strawberry Digital. I designed and built all nine myself. They aren't
public repos, so the links go to the live products.

| Product | What it is |
| --- | --- |
| [MTT Hold'em](https://mttholdem.com) | Interactive tournament-poker trainer. 136 lesson hands street by street plus a graded 100-hand exam covering push/fold, ICM, and M-zone play. |
| [Happenin'](https://happenin.city) | Events and places across 50+ US metros. Chosen, not crowdsourced. |
| [EggBoo](https://eggboo.com) | Automated product-research and deals engine with live marketplace pricing and buying guides. |
| [Mochi Meadows](https://mochimeadows.app) | Cozy offline math game for kids: arithmetic through fractions, decimals, and shapes. |
| [Midsentence](https://midsentence.app) | A speed reader with a point of view: one word at a time, at a pace authored for each piece. No library, no import button, no settings, no speed slider. |
| [Callsong](https://callsong.app) | Call-and-response vocal-pitch trainer built on the expanding-scale warm-up. Plays each phrase on sampled piano, then listens as you sing it back and scores every note in cents. |
| [SuddenStay](https://suddenstay.com) | Last-minute hotel and resort deals across Florida. Each listing names the catch up front and links straight to the live price. |
| [Tally](https://tally.strawberrydigital.llc) | Your bank sees $87.42 at the grocery store. Tally reads the receipt and keeps every line on it. |
| [Metal Vision](https://metalvision.app) | A Meta Quest game about getting both eyes to play together. Each eye sees its own image, and you tune the two until they lock into one. |

---

## Stack

- **AI and agents:** LLM architecture, agent workflows, tool calling, orchestration, RAG, evaluation
  frameworks (including LLM-as-judge), structured outputs, vector search, multi-agent systems,
  context engineering, agent observability and tracing, self-improvement loops, MCP.
- **Models, hands-on:** Anthropic Claude, OpenAI, Google Gemini.
- **Languages:** TypeScript, JavaScript, Python, Node.js, SQL, C#.
- **Web:** React, Next.js, FastAPI.
- **Data and infra:** PostgreSQL, Supabase, Redis, Docker, Kubernetes, Terraform, Firestore.
- **Cloud:** AWS, GCP (Cloud Run, Cloud Scheduler, Vertex AI, Secret Manager), Azure, Vercel.

---

## Background

**Founding roles**

- **Calibrate Group**, Founding AI Technical Lead, 2026 to present. See above.
- **Strawberry Digital**, Founder, 2025 to present. Independent software studio behind the products above.
- **Beesla**, Founder & AI Product Lead, 2025 to present. See above.
- **JobPhaze**, Cofounder & Founding Engineer, 2024 to 2025. Early-stage HR SaaS. Owned architecture
  from the services layer down to cloud infrastructure, and stood up CI/CD, testing, IaC, and
  monitoring from scratch.
- **Weaver**, Cofounder & Founding Engineer, 2023 to 2024. Early-stage consumer dating app. Owned
  architecture and technical direction, and designed backend systems and data models for
  multi-client usage.

**Engineering management**

- **Spekit**, Software Engineering Manager, 2022. Series A SaaS. Scaled the team from 3 to 20+, and
  owned hiring, engineering standards, on-call culture, and code review.
- **PwC**, Software Engineering Manager, 2020 to 2021. Led development within a ~60 person
  engineering organization delivering a cloud-based enterprise platform, working directly with
  business stakeholders in a regulated environment.
- **LoanLogics**, Software Engineering Manager, 2018 to 2019. Built and led a team of 15 to deliver
  v1.0 of a cloud-based underwriting platform in regulated fintech. Microservices on AWS with CI/CD.

**Earlier**

- **iProcedures**, Tech Lead Software Engineer, 2016 to 2018. Led development of a real-time clinical
  platform for anesthesia and surgical monitoring, shipped on iPad in a HIPAA-regulated environment.

MS in Computer Engineering, University of South Florida.

---

## Links

- Site: [mattspaulding.org](https://www.mattspaulding.org)
- LinkedIn: [linkedin.com/in/spauldingmatthew](https://linkedin.com/in/spauldingmatthew)
- Beesla: [beesla.com](https://beesla.com)
