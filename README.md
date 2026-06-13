# Hi, I'm Conrado 👋

**AI Infrastructure Engineer · On-Prem AI Specialist · SaaS Founder**  
📍 Macapá, Brazil · 🌐 Available for remote consulting · 💬 English & Portuguese

---

## About Me

I design and build **production-grade AI systems that run entirely on-premise** — no cloud dependency, no vendor lock-in. My stack combines local LLMs (Ollama), multi-agent orchestration, persistent memory layers, and a personal benchmark methodology validated across 19 models.

25+ years in IT infrastructure (Linux, networks, security) meet hands-on AI research: I build frameworks, run benchmarks, publish papers, and ship products — on the same hardware, in the same lab.

I work at the intersection of **deep infrastructure knowledge** and **modern AI engineering**, which means I can build things that actually run reliably in production — not just demos.

---

## 🚀 Featured Projects

### [AgentForge](https://github.com/JConradoN/agent-FORGE) — On-Premise Multi-Agent Framework · *Open Source*

Python framework for building LLM agents that run entirely on local hardware. Spec-first, runtime-driven, empirically validated.

- **Core thesis:** *"20% is the model, 80% is the runtime"* — validated across 19 local models over 4 months of benchmarks ([ABS](https://github.com/JConradoN/agent-benchmark-suite) → [LOP](https://github.com/JConradoN/LOP) → [FORGE](https://github.com/JConradoN/FORGE) → [REAL](https://github.com/JConradoN/REAL))
- **Results:** FORGE F3 94.4% · REAL P4 91.7% with `qwen3.5:27b` on consumer hardware
- **Features:** spec-first YAML agents · active guardrails · autonomous reflection · tool registry (agents that create tools) · 4 channels (CLI, HTTP, MCP, Telegram) · multi-agent orchestration · 296 tests
- **Memory layer:** 3-tier persistent memory — SQLite (structured) · Qdrant/mem0 (semantic) · Kuzu graph (causal)
- **Hardware:** Xeon E5-2696v3 · 128 GB ECC · dual RTX 3060 (24 GB VRAM) — no cloud required
- 📂 [Repository](https://github.com/JConradoN/agent-FORGE)

---

### [Chefs Office](https://www.chefsoffice.com.br) — SaaS for Professional Chefs · *Live in Production*

A full-featured web platform for managing gastronomic technical sheets (recipe costing, ingredient control, nutritional data, PDF export, AI-powered import).

- **Stack:** React 18 + TypeScript + Tailwind + shadcn/ui · Supabase (PostgreSQL + Auth + Edge Functions) · Gemini 2.0 Flash · jsPDF · Lovable · n8n (self-hosted)
- **AI Features:** PDF/DOCX/image import with automatic ingredient extraction via Gemini 2.0 Flash · 4-layer SmartImporter resolution · fallback model handling
- **Scale:** 320-ingredient global catalog (TACO/USDA) · chained sub-recipes · multi-establishment · CMV% alerts · professional PDF export
- **Dev workflow:** Claude Code + Gemini + Lovable · AI-first, solo-built from architecture to deploy
- 📂 [Showcase & docs](https://github.com/JConradoN/chefs-office-showcase) · 🌐 [chefsoffice.com.br](https://www.chefsoffice.com.br)

---

## 🛠️ Tech Stack

**Infrastructure & Security**
```
Linux (Red Hat · Debian · Ubuntu · FreeBSD)   Windows Server · Active Directory
TCP/IP · Routing · VPN · Firewall (iptables)  Squid · Snort · Apache · DNS · LDAP
Pentest · Security Hardening                  25+ years hands-on
```

**AI & Development**
```
Python · PostgreSQL · Docker · Supabase       REST APIs · Edge Functions (Deno)
Prompt Engineering · Fine Tuning · RAG        STT / TTS · On-premise LLM agents
n8n (autonomous agents & automations)         Claude Code · Lovable · Gemini API
React + TypeScript · Tailwind CSS             LLM Orchestration (Claude · Gemini)
```

---

## 🔬 Research & Methodology

**Benchmark Methodology — 4-Stage Model Certification Funnel**

19 local models entered. Each stage is an elimination gate. Only models that pass all 4 are considered production-ready and deployed in agent-FORGE.

| Stage | Gate question | Repo |
|-------|--------------|------|
| **ABS** | Can it call tools at all? | [agent-benchmark-suite](https://github.com/JConradoN/agent-benchmark-suite) |
| **LOP** | Does it hold under real operational pressure? | [LOP](https://github.com/JConradoN/LOP) |
| **FORGE** | Can it function as an agent? Multi-turn, chained, autonomous? | [FORGE](https://github.com/JConradoN/FORGE) |
| **REAL** | Does it work in production? Real browser, real tests, no shortcuts? | [REAL](https://github.com/JConradoN/REAL) |
| **agent-FORGE** | *Deploy* — production runtime for models that earned it | [agent-FORGE](https://github.com/JConradoN/agent-FORGE) |

- **llms-on-prem** — independent research on the viability of on-premise LLMs for production use. Core finding: *architectural quality is the primary predictor; within good families, scale delivers.*
- **KDMILE 2026** — paper submitted to the Brazilian Symposium on Knowledge Discovery and Intelligent Systems (Jun 2026).

---

## 💼 What I Build for Clients

- **On-Premise AI Infrastructure** — production multi-agent systems on local hardware, zero cloud dependency
- **AI Automation** — n8n workflows + LLMs, process automation, API integrations
- **SaaS with AI** — full-stack products with Supabase + React + embedded AI features
- **Infrastructure & Security** — Linux hardening, networking, VPN, firewall — 25+ years hands-on

---

## 📌 Other Projects

| Project | Description | Stack |
|---|---|---|
| [forte.jus](https://github.com/JConradoN/forte.jus-showcase) | On-premise AI legal assistant — RAG over court files + PJe/TJAP integration. Zero data leaves the office. | Python · FastAPI · Qdrant · Ollama |
| [Claudio](https://github.com/JConradoN/claudio) | Autonomous agent via Telegram — multi-agent workflows, local LLM, persistent memory | Go · Ollama |
| [network-diagnoser-ai](https://github.com/JConradoN/network-diagnoser-ai) | AI-powered network diagnostics with real-time NOC dashboard — ARP, SNMP, MikroTik, LLM analysis | Python · Docker |

---

## 📫 Get in Touch

- 💼 Open to freelance projects — **preferably USD/EUR**
- 📧 [jconrado@gmail.com](mailto:jconrado@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/conrado-nogueira-ti)

---

*"I don't just use AI tools — I build the infrastructure they run on."*
