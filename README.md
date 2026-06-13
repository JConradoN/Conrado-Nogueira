# Conrado-Nogueira
Meu perfil pessoal com informações curriculares. 

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

- **Core thesis:** *"20% is the model, 80% is the runtime"* — validated across 19 local models over 4 months of benchmarks (ABS → LOP → FORGE → REAL)
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

- **ABS — Agent Benchmark Suite** — personal benchmark methodology for evaluating local LLMs on tool use, reasoning, and agentic tasks. Ran 19 models through 4 progressive stages (ABS → LOP → FORGE → REAL).
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
| [AgenteBIA](https://github.com/JConradoN/DIO-BOOTCAMP-Genai-Dados-AgenteBIA) | AI agent — DIO Bootcamp | Python · GenAI |
| [NotebookLM Study](https://github.com/JConradoN/DIO-BOOTCAMP-Genai-Dados-NotebookLM) | AI-powered study methodology | NotebookLM |
| [Graham.io](https://github.com/JConradoN/DIO-BOOTCAMP-Projeto_final-GRAHAM-IO_Last) | Final Bootcamp project | Python |

---

## 📫 Get in Touch

- 💼 Open to freelance projects — **preferably USD/EUR**
- 📧 [suporte@chefsoffice.com.br](mailto:suporte@chefsoffice.com.br)
- 🔗 [LinkedIn](https://www.linkedin.com/in/conrado-nogueira-ti)

---

*"I don't just use AI tools — I build the infrastructure they run on."*
