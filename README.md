# Matt Spaulding

**AI Product Engineer & Technical Leader**

Tampa, Florida. Remote. Open to senior AI engineering and technical product roles.

I design and ship production AI systems: agent orchestration, retrieval, tool calling, and evaluation
loops. 15+ years building software that ships and stays stable, hands-on across architecture and
delivery, from first prototype to production. I work at the intersection of product decisions and
engineering execution, and I sit with the customers who use what gets built.

[mattspaulding.org](https://www.mattspaulding.org) · [LinkedIn](https://linkedin.com/in/spauldingmatthew) · [GitHub](https://github.com/mattspaulding)

---

## Featured projects

### [Actuary](https://github.com/mattspaulding/actuary)

**The paying watchdog: the agent economy, measured.** (Aug 2026)

An autonomous probe fleet that continuously buys from services on Circle's Agent Marketplace with
real USDC nanopayments, grades what comes back with Gemini, and sells the resulting trust scores to
other agents at $0.001 per lookup. Billed as "Moody's plus Pingdom for machine commerce": a
reputation layer that funds its own observations.

- Every observation is a real paid transaction, not a synthetic ping.
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
and tunes itself: how many evals to generate, what confidence threshold to use, when to ask for help.

**Verified result:** detected a real regression (ambiguous source currency silently defaulted to
USD), generated 10 eval cases, and lifted pass rate from 4/10 to 10/10, a +60% lift.

**Stack:** Google ADK (Python), Gemini 3 on Vertex AI, Arize Phoenix + Phoenix MCP, Slack Block Kit,
Cloud Run, Cloud Scheduler, Firestore.

[Live demo](https://mender-thj3gr276a-uc.a.run.app)

---

## Beesla

**Founder & AI Product Lead**, Apr 2025 to present · [beesla.com](https://beesla.com)

AI-native platform that converts natural language into structured workflows: agent orchestration,
retrieval, tool calling, and evaluation loops on Anthropic Claude. Reached **1M+ impressions** across
search engines and AI assistants and **80K+ unique users**.

TypeScript, Node, React, Next.js, Docker, Vercel, Supabase (PostgreSQL), Anthropic Claude, vector search.

---

## Shipped products

Independent studio work through Strawberry Digital, solo designed, built, and shipped. These are not
public repos, so the links go to the live products.

| Product | What it is |
| --- | --- |
| [MTT Hold'em](https://mttholdem.com) | Interactive tournament-poker trainer. 136 lesson hands street by street plus a graded 100-hand exam covering push/fold, ICM, and M-zone play. |
| [Happenin'](https://happenin.city) | Curated events and places discovery across 50+ US metros. Chosen, not crowdsourced. |
| [EggBoo](https://eggboo.com) | Automated product-research and deals engine with live marketplace pricing and buying guides. |
| [Mochi Meadows](https://mochimeadows.app) | Cozy offline math game for kids: arithmetic through fractions, decimals, and shapes. |
| [Midsentence](https://midsentence.app) | A speed reader with a point of view. RSVP style, one word at a time in a fixed spot, at a pace authored per piece. No library, no import button, no speed slider. |
| [Callsong](https://callsong.app) | Call-and-response vocal-pitch trainer built on the expanding-scale warm-up. Plays each phrase on sampled piano, listens as you sing it back, and scores every note in cents. |

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

**Founder and founding engineer**

- **Beesla**, Founder & AI Product Lead, 2025 to present. See above.
- **JobPhaze**, Cofounder & Founding Engineer, 2024 to 2025. Early-stage HR SaaS. Owned architecture
  across services, data pipelines, and cloud infrastructure, and stood up CI/CD, testing, IaC, and
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

MS in Computer Engineering, University of South Florida. Founder Institute graduate.

---

## Links

- Site: [mattspaulding.org](https://www.mattspaulding.org)
- LinkedIn: [linkedin.com/in/spauldingmatthew](https://linkedin.com/in/spauldingmatthew)
- Beesla: [beesla.com](https://beesla.com)
