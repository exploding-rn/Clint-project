# CLINT
### Creative Lined Intuitive Neural Technology
#### OWUI · Ollama · Anthropic · Google Gemini · Custom Model Training · Obsidian Infrastructure Project · Llama.cpp
> Personal self-hosted AI infrastructure and model development — my living AI portfolio.
*Repo created 3/15/2026 — project maintained since 1/25/2026*
---
## 🧠 What is CLINT?
CLINT (Creative Lined Intuitive Neural Technology) is my personal self-hosted AI stack and model development project. The goal is a fully private, locally-run AI environment with no reliance on big tech — integrating local models, cloud APIs, voice, knowledge management, and custom trained models built from scratch.

CLINT is also the name of the first model developed under this project — a fine-tuned Gemma3 9B trained on a 1137-example distillation dataset generated from Claude, Gemma, Ministral, Granite, and Llama models.

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
| **Unsloth** | Model fine-tuning framework |
| **LLama3.2, Minstral, Granite, and Gemma3** | Base model for CLINT fine-tune |
| **n8n** | Automations |
|**llama.cpp| More Local Models|

---
## 🖥️ Services & Ports
| Service | Port | Host |
|---|---|---|
| Open WebUI | 3000 | Docker Main PC |
| SearXNG | 7846 | Docker Main PC |
| Kokoro TTS | 8880 | Docker Main PC |
| Pi-hole | 8888 | Raspberry Pi 5 |
| Nginx Proxy Manager | 81 | Raspberry Pi 5 |
| Homarr Dashboard | 7575 | Raspberry Pi 5 |
| Gotify | 8070 | Raspberry Pi 5 |
| n8n | 5678 | Docker Main PC |

---
## 🤖 CLINT Model — v0.1
First custom model trained under the CLINT Industries project.

| Property | Value |
|---|---|
| **Base model** | Gemma3 9B |
| **Training method** | QLoRA fine-tune via Unsloth |
| **Dataset size** | 1137 examples |
| **Dataset sources** | Claude Sonnet (137), Gemma3 4B (250), Ministral 14B (200), Granite Code 8B (200), Granite3.3 8B (200), Llama 3.2 3B (150) |
| **Specializations** | General reasoning, vision, long context |
| **Hardware** | RTX 3080 10GB + Ryzen 9 9950X3D + 32GB RAM |
| **Status** | Training in progress |

---
## 📅 Changelog
### January 2026
- Added Open WebUI
- Added Ollama integration with OWUI

### February 2026
- Nothing (we don't talk about February) I didnt do anything in febuary

### March 2026
- Added Google Gemini free tier API
- Added paid Anthropic (Claude) API
- Linked Obsidian vault with OWUI
- Built local voice clone (not yet hooked into OWUI)
- Added SearXNG private search on port 7846
- Created GitHub repo
- Rebranded from OPNIX to CLINT Industries
- Built multi-model training data pipeline (5 models + Claude API)
- Generated 1137-example distillation dataset for CLINT v0.1
- Fine-tuning Gemma3 9B as first CLINT model
- added llama.cpp

---
## 🗺️ Roadmap
- [ ] Finish CLINT v0.1 fine-tune and push to Ollama
- [ ] Hook voice clone into OWUI
- [ ] RAG pipeline — vector DB (Qdrant) pointed at Obsidian vault
- [✅]Pipelines-based Obsidian note writing function
- [✅] Stable Diffusion / local image generation
- [ ] CLINT v0.2 — larger dataset with more Claude gold standard examples

---
## 📜 License
Apache 2.0 License (same as MIT but adds Patent Protection)

---
*Built by Keller — 13 y/o home lab enthusiast & founder of CLINT AI Models*
