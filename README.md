# OPNIX 
### OWUI · Ollama · Anthropic · Google Gemini · Kubernetes · K3s · Obsidian Infrastructure Project

> Personal self-hosted AI infrastructure — my living AI portfolio.

*Repo created 3/15/2026 — project maintained since 1/25/2026*

---

## 🧠 What is OPNIX?

OPNIX is my personal self-hosted AI stack. The goal is a fully private, locally-run AI environment with no reliance on big tech — integrating local models, cloud APIs, voice, knowledge management, and eventually a multi-node Kubernetes cluster.

---

## 📦 Stack

| Component | What it does |
|---|---|
| **Open WebUI (OWUI)** | Main AI chat interface |
| **Ollama** | Local model runner (LLMs on-device) |
| **Anthropic API** | Claude integration via paid API |
| **Google Gemini API** | Gemini free tier integration |
| **Obsidian** | Personal knowledge base / second brain |
| **SearXNG** | Private self-hosted search engine |
| **Kokoro TTS** | Text-to-speech with custom voice clone |
| **Raspberry Pi 5** | Always-on services (Pi-hole, Tailscale, Nginx, etc.) |
| **Tailscale** | Private mesh network across all devices |

---

## 🖥️ Services & Ports

| Service | Port | Host |
|---|---|---|
| Open WebUI | 3000 | Main PC |
| SearXNG | 7846 | Main PC |
| Kokoro TTS | 8880 | Main PC |
| Pi-hole | 8888 | Raspberry Pi 5 |
| Nginx Proxy Manager | — | Raspberry Pi 5 |
| Homarr Dashboard | — | Raspberry Pi 5 |
| Gotify | — | Raspberry Pi 5 |

---

## 📅 Changelog

### January 2026
- Added Open WebUI
- Added Ollama integration with OWUI

### February 2026
- Nothing (we don't talk about February)

### March 2026
- Added Google Gemini free tier API
- Added paid Anthropic (Claude) API
- Linked Obsidian vault with OWUI
- Built local voice clone (not yet hooked into OWUI)
- Added SearXNG private search on port 7846
- Created GitHub repo

---

## 🗺️ Roadmap

- [ ] Hook voice clone into OWUI
- [ ] RAG pipeline — vector DB (Qdrant) pointed at Obsidian vault
- [ ] K3s multi-node cluster across 3 machines
- [ ] Pipelines-based Obsidian note writing function
- [ ] Stable Diffusion / local image generation
- [ ] Full Kubernetes migration

---

## 📁 Repo Structure

```
OPNIX/
├── docker/          # Docker compose files per service
├── configs/         # Service configs (SearXNG, OWUI, etc.)
├── scripts/         # Automation & setup scripts
├── pi/              # Raspberry Pi specific configs
└── README.md
```

---

## 📜 License

APCAHE 2.0 licesne (same as MIT but addes Patent Protection)

---

*Built by Keller — 13 y/o home lab enthusiast*
