
# CLINT

[](https://github.com/exploding-rn/Clint-project#clint)

### Creative Lined Intuitive Neural Technology

[](https://github.com/exploding-rn/Clint-project#creative-lined-intuitive-neural-technology)

#### OWUI · Ollama · Anthropic · Google Gemini · Custom Model Training · Obsidian Infrastructure Project · Llama.cpp · LM Studio · Mistral · Groq

[](https://github.com/exploding-rn/Clint-project#owui--ollama--anthropic--google-gemini--custom-model-training--obsidian-infrastructure-project--llamacpp)

> Personal self-hosted AI infrastructure and model development — my living AI portfolio. _Repo created 3/15/2026 — project maintained since 1/25/2026_
> also note that was just on this current PC in total AI infrastructure had started in mid march of 2024.

---

## 🧠 What is CLINT?

[](https://github.com/exploding-rn/Clint-project#-what-is-clint)

CLINT (Creative Lined Intuitive Neural Technology) is my personal self-hosted AI stack and model development project. The goal is a fully private, locally-run AI environment with little reliance on big tech — integrating local models, cloud APIs, voice, knowledge management, and custom trained models built from scratch.

CLINT is also the name of the first model developed under this project — a fine-tuned Gemma3 9B trained on a 1137-example distillation dataset generated from Claude, Gemma, Ministral, Granite, and Llama models also trained with Opus 4.6 (10000x, https://huggingface.co/datasets/Roman1111111/claude-opus-4.6-10000x) .

---

## 📦 Stack

[](https://github.com/exploding-rn/Clint-project#-stack)

| Component                                   | What it does                                         |
| ------------------------------------------- | ---------------------------------------------------- |
| **Open WebUI (OWUI)**                       | Main AI chat interface                               |
| Open WebUI (OWUI) (BACKUP SERVER)           | Backup interface                                     |
| **Ollama**                                  | Local model runner (LLMs on-device)                  |
| **Anthropic API**                           | Claude integration via paid API                      |
| **Google Gemini API**                       | Gemini free tier integration                         |
| **Obsidian**                                | Personal knowledge base / second brain               |
| **SearXNG**                                 | Private self-hosted search engine                    |
| **Kokoro TTS**                              | Text-to-speech with custom voice clone               |
| **Raspberry Pi 5**                          | Always-on services (Pi-hole, Tailscale, Nginx, etc.) |
| **Tailscale**                               | Private mesh network across all devices              |
| **Unsloth**                                 | Model fine-tuning framework                          |
| **LLama3.2, Minstral, Granite, and Gemma3** | Base model for CLINT fine-tune                       |
| **n8n**                                     | Automations                                          |
| **llama.cpp**                               | More Local Models                                    |
| **LM studio**                               | EVEN MORE MODELS!                                    |

---

## 🖥️ Services & Ports

[](https://github.com/exploding-rn/Clint-project#️-services--ports)

| Service             | Port    | Host                          | Maintained |
| ------------------- | ------- | ----------------------------- | ---------- |
| Open WebUI          | 3000    | Docker Main PC/Raspberry PI 5 | ✅          |
| SearXNG             | 7846    | Docker Main PC                | ❌          |
| Kokoro TTS          | 8880    | Docker Main PC                | ❌          |
| Pi-hole             | 8888    | Raspberry Pi 5                | ✅          |
| Nginx Proxy Manager | 81      | Raspberry Pi 5                | ✅          |
| Homarr Dashboard    | 7575    | Raspberry Pi 5                | ❌          |
| Gotify              | 8070    | Raspberry Pi 5                | ❌          |
| n8n                 | 5678    | Docker Main PC                | ✅          |
| Hermes              | 9119    | Main PC WSL/Raspberry Pi 5    | ✅          |
| OpenClaw            | 18789   | Main PC/Raspberry PI 5        | ❌          |
| Home Assistant      | 8123    | Raspberry Pi 5                | ✅          |
| Custom Model        | N/A     | Main PC                       | ❌          |
| Comfy UI            | 8000    | Main PC                       | ✅          |
| Ollama              | 11434   | Main PC/Raspberry PI 5        | ✅          |
| Llama.cpp           | DEFUALT | WSL2 Main PC                  | ❌          |


---

## 🤖 CLINT Model — v0.1

[](https://github.com/exploding-rn/Clint-project#-clint-model--v01)

First custom model trained under the CLINT Industries project.
### **NOT MAINTAINED CURRENTLY**

WILL CONTUINE SOON.. ish

| Property            | Value                                                                                                                                                                                                             |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Base model**      | Gemma3 9B                                                                                                                                                                                                         |
| **Training method** | QLoRA fine-tune via Unsloth                                                                                                                                                                                       |
| **Dataset size**    | 1137 examples custom made + 10000                                                                                                                                                                                 |
| **Dataset sources** | Claude Sonnet (137), Gemma3 4B (250), Ministral 14B (200), Granite Code 8B (200), Granite3.3 8B (200), Llama 3.2 3B (150), Opus 4.6 (10000x, https://huggingface.co/datasets/Roman1111111/claude-opus-4.6-10000x) |
| **Specializations** | General reasoning, vision, long context                                                                                                                                                                           |
| **Hardware**        | RTX 3080 10GB VRAM + Ryzen 9 9950X3D + 32GB RAM                                                                                                                                                                   |
| **Status**          | DISCONTUINED DUE TO TIME RESTRICTION                                                                                                                                                                              |

---

## 📅 Changelog

[](https://github.com/exploding-rn/Clint-project#-changelog)
### BEFORE 2026
- Used OWUI + Ollama on Intel insperation 7700
- Used NGROK to expsose port 3000 for OWUI
### January 2026

[](https://github.com/exploding-rn/Clint-project#january-2026)

- Switched to Custom built PC
- Added Open WebUI
- Added Ollama integration with OWUI

### February 2026

[](https://github.com/exploding-rn/Clint-project#february-2026)

- Nothing (we don't talk about February) I didnt do anything in febuary

### March 2026

[](https://github.com/exploding-rn/Clint-project#march-2026)

- Added Google Gemini free tier API
- Removed Google Gemini free tier API
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

### APRIL 2026
##### - Computer Outage!!!
- OWUI on pi5 for model and API testing
- Added Open Claw
- created custom css for OWUI to be accent color #FA6000 or RGBA: (250, 96, 0, 1)

### MAY 2026
- Added Hermes
- Removed Open Claw from main stack
- Added mistrel free teir
- Added LM studio
- Added Home Assistant
- 


---

## 🗺️ Roadmap

[](https://github.com/exploding-rn/Clint-project#️-roadmap)


- [ ]  Hook voice clone into OWUI
- [ ]  RAG pipeline — vector DB (Qdrant) pointed at Obsidian vault
 [ ]Pipelines-based Obsidian note writing function
- [✅] Stable Diffusion / local image generation

---

## 📜 License

[](https://github.com/exploding-rn/Clint-project#-license)

Apache 2.0 License (same as MIT but adds Patent Protection)

---

_Built by Keller — 14 y/o home lab enthusiast
