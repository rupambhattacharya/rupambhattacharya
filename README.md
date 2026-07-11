### Hi, I'm Rupam 👋

Senior software engineer in Munich building production LLM systems, cloud platforms, and full-stack applications. Currently at **ProSieben Media SE**, leading platform and AI engineering for Live TV AdTech serving 25M+ daily users. AWS Certified Solutions Architect — Professional. M.Sc. AI & Distributed Systems, TU Munich.

- 📝 Blog: [rupambhattacharya.github.io](https://rupambhattacharya.github.io)
- 💼 LinkedIn: [rupam-bhattacharya](https://www.linkedin.com/in/rupam-bhattacharya-29884714/)
- 📫 Email: [rupam.speaks@gmail.com](mailto:rupam.speaks@gmail.com)

---

### 🔭 Currently focused on

- **Agent interpretability** — understanding *why* an agent made a tool call or decision, not just what it output
- **Agent security** — scoped tool permissions, read-only access enforced at every independent layer (IAM, FGAC, tool definitions), prompt-injection resistance
- **Agent observability** — auditing every tool call and inference, per-session/per-model cost tracking, budget alerts
- **LLMOps & automated testing** — treating prompts and skills as versioned, deployable artefacts with evaluation pipelines (LLM-as-judge scoring, scenario-based agent evaluation) as a release gate across multiple model providers
- **Agent orchestration** — multi-agent delegation (orchestrator → planner → coder/designer), complexity-based model routing, agent-to-agent protocols

Most of this is coming together in [**llm-collab**](https://github.com/rupambhattacharya/llm-collab), an open-source CLI for AI-powered multi-agent collaboration — MCP tooling, cost/audit hooks, and a skills system built around exactly these ideas. I write about the underlying patterns at [rupambhattacharya.github.io/#blog](https://rupambhattacharya.github.io/#blog).

---

### 🏗️ Selected work

- **Natural-language interface to OpenSearch** (ProSieben) — Claude tool-use agent letting product/engineering query a production analytics cluster in plain English, with defence-in-depth read-only access across IAM, FGAC, and tool-definition layers
- **GenAI developer agent CLI** (ProSieben) — multi-provider agentic CLI with a multi-LLM evaluation pipeline benchmarking quality, cost, and latency; prompts shipped as versioned artefacts with release/rollback
- **AWS platform migration — Live TV AdTech** (ProSieben) — shared-account to per-team isolation, ECS EC2 → Fargate, CI/CD rebuild; 90% fewer platform vulnerabilities, 68% faster pipelines, €8k/month saved
- **Self-service multi-brand publishing platform** (Burda Forward) — shared content platform across 200+ publishers, plus a proxy API serving 5M+ daily ad requests

---

### 🛠️ What I build with

**AI/LLM** — Agentic systems & tool calling · Multi-LLM evaluation pipelines · Prompt/skill versioning · Anthropic & OpenAI APIs · MCP
**Cloud/Platform** — AWS (Lambda, ECS Fargate, EKS, DynamoDB, OpenSearch) · Terraform · GitLab CI / GitHub Actions · Datadog
**Full-stack** — Next.js · React · Vue · Angular · Node.js/TypeScript
**Languages** — Python · TypeScript · Go · Java · Rust

---

### A bit more

Outside engineering I sing and play keyboard — classically trained, now writing and performing contemporary work with [Smile Project](https://smilemunich.wordpress.com/), a Munich ensemble that performs for people who can't easily get to concerts. Based in Munich, originally from Agartala, India.

*"There are only two ways to live your life. One is as though nothing is a miracle. The other is as though everything is a miracle."* — Albert Einstein
