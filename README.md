# Hi, I'm Aarav Mittal

**Building AI products that reason, retrieve, and remember** — and the product systems that put them in users' hands.

🎓 **B.S. Computer Science**, **B.S. Electrical Engineering**, **B.S. Innovative Leadership & Engineering Entrepreneurship**  
**University of Illinois Urbana-Champaign (Grainger)** · Class of 2029  
📍 Chicago, IL

---

# About Me

I'm a CS / EE / ILEE student at UIUC focused on **AI systems and product**: agents and pipelines that can **reason** over goals and constraints, **retrieve** the right context, and **remember** what matters across a session — then shipping that as software people actually use.

I've worked at **Databricks** and **Rivian**, and I build end-to-end AI products — from document and multimodal understanding to AI-native planning.

---

# Currently Interested In

- Agentic AI & reliable tool-using systems
- Retrieval, long-term memory, and context management
- LLM evaluation, grounding, and product reliability
- AI infrastructure & platforms
- AI product engineering (scope → ship → iterate)

---

# Experience

## Databricks — Software Engineer

**Present** · Focused on **open-source AI / Omnigent**

- Software Engineer on open-source **AI agent** infrastructure around **[Databricks Omnigent](https://www.databricks.com/blog/introducing-omnigent-meta-harness-combine-control-and-share-your-agents)** — a meta-harness for composing, controlling, and sharing agents
- Work spans agent composition across harnesses and models, policy/control at the meta-harness layer, and infrastructure that helps agentic products ship reliably
- Omnigent: [github.com/omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent) · [omnigent.ai](https://omnigent.ai/)

---

## Rivian — Software Engineer

**Present**

- Software engineering in a high-reliability product environment
- Building software across systems and application layers for real-world products

---

# AI Products

Products oriented around the same loop: **reason → retrieve → remember** (and act).

## Chronos — AI-Native Planner

**Natural language in. Constraint-backed calendar out.** Chronos interprets planning intent with an AI/deterministic planner, then a verified scheduling engine places blocks — so the model never invents capacity the calendar can't support.

**How it maps to the thesis**

- **Reason** — parses multi-spot asks (“find me 3 spots, each 2 hours”), priorities, deadlines, and preferences into structured tasks and constraints
- **Retrieve** — pulls the user's availability, protected time, and existing schedule as the ground truth for placement
- **Remember** — persists per-user tasks, constraints, and diagnostics so the week stays explainable and editable

**Highlights**

- AI planner (always-on deterministic parser + optional LLM refine) separate from the **SchedulingEngine** source of truth
- Diagnostics when work can't fit; FullCalendar drag/resize; JWT multi-user; America/Chicago time rules
- Stack: Python · FastAPI · React · TypeScript · constraint scheduling

**GitHub:** [a2105z/Chronos](https://github.com/a2105z/Chronos)

---

## CoParse — Document AI Product

**Contract safety for students, renters, and early-career workers** — upload an agreement; the product **retrieves** clauses that matter, **reasons** about risk in context, and surfaces plain-English explanations plus questions to ask before you sign.

**How it maps to the thesis**

- **Retrieve** — extract and surface risky / material clauses from long contracts
- **Reason** — role-aware analysis and missing-protection style checks
- **Remember** — structured analysis jobs and results users can revisit before signing

**Highlights**

- Full AI product loop: upload → extract → analyze → explain → actionable questions
- Kotlin / Jetpack Compose Android client · FastAPI + PostgreSQL backend
- Stack: Kotlin · Compose · FastAPI · PostgreSQL · Document AI / NLP

**GitHub:** [a2105z/CoParse](https://github.com/a2105z/CoParse)

---

## TeXForm — Multimodal AI Product

Handwritten notes → LaTeX. A vision/OCR product that **retrieves** line and math structure from scans, **reasons** about handwriting vs. formulas, and outputs usable `.tex` / PDF — with a live Hugging Face demo.

**How it maps to the thesis**

- **Retrieve** — segment pages and pull the right visual evidence per line
- **Reason** — handwriting OCR + math recognition paths (TrOCR and optional formula engines)
- **Remember** — assemble a coherent document artifact the user can download and reuse

**Highlights**

- End-to-end multimodal pipeline productized as React + FastAPI (Docker + HF Spaces)
- Designed for a real notes-in / LaTeX-out workflow, not just a notebook demo
- Stack: Python · FastAPI · React · TrOCR · Hugging Face · OCR / VLM

**Live demo:** [Hugging Face Space](https://huggingface.co/spaces/amittal417/texform) · **GitHub:** [a2105z/TeXForm](https://github.com/a2105z/TeXForm)

---

# Software & Product Builds

Smaller full-stack and product/PM-shaped apps — shipping UX, scope, and iteration, not model-first systems.

| Project | What it is |
|---------|------------|
| **[Meridian](https://github.com/a2105z/Meridian)** | Full-stack academic journey tracker — awards, scores, goals, auth-scoped data, analytics, export (FastAPI + React) |
| **[Cosmos](https://github.com/a2105z/Cosmos)** | TI-84–inspired browser calculator — calc, graph, and AP Stats modes ([live](https://a2105z.github.io/Cosmos/)) |
| **[CoolGames.io](https://github.com/a2105z/CoolGames.io)** | Classic browser games product — Chess, Tetris, Snake, Pong, 2048, and more; no accounts ([live](https://a2105z.github.io/CoolGames.io/)) |

---

# Looking For

**Software Engineering, AI Engineering, and AI Product internships**, especially:

- Agentic AI & AI infrastructure
- Retrieval / memory / context systems
- LLM platforms and evaluation
- AI product engineering

If you're building in these areas, I'd love to connect.
