# 👋 Hey, I’m Chris

**Security Researcher | Self-Taught Developer | Local LLM & Autonomous Agent Builder**

Building **PenMaster Security** — an autonomous penetration testing agent powered by local models. I work at the intersection of security, AI, and infrastructure.

-----

## 🚀 What I’m Working On

I’m obsessed with:

- 🔐 **Autonomous Security Agents** — orchestrating pentest workflows with local LLMs (Qwen 2.5-14B via LM Studio)
- 🧠 **Local AI Deployment** — optimizing models for on-device inference (no cloud, no API keys)
- 🛠️ **Security Tooling** — building agents that coordinate masscan, nmap, sqlmap, hydra, and 13 other security tools
- 📱 **Mobile Security** — porting models to iOS/Android for offline vulnerability assessment
- 🔄 **Agent Infrastructure** — memory systems, logging, negative experience caching, decision tracking

-----

## 💻 Tech Stack

### Languages & Core

![Python](https://img.shields.io/badge/Python-3.9+-3776ab?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4.0+-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Kali-000000?style=flat-square&logo=linux&logoColor=white)

### AI & Models

![Qwen](https://img.shields.io/badge/Qwen-2.5--14B-blue?style=flat-square)
![LM Studio](https://img.shields.io/badge/LM%20Studio-Local%20Inference-blueviolet?style=flat-square)
![GGUF](https://img.shields.io/badge/GGUF-Q4__K__M-orange?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Tool%20Orchestration-green?style=flat-square)

### Infrastructure & Tools

![Flask](https://img.shields.io/badge/Flask-MCP%20Server-000000?style=flat-square&logo=flask)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-M1%20MacBook-555555?style=flat-square&logo=apple&logoColor=white)
![UTM](https://img.shields.io/badge/UTM-VM%20Management-4B0082?style=flat-square)

### Security

- **Recon:** masscan, nmap, nikto
- **Exploitation:** sqlmap, hydra, ncrack, searchsploit
- **Payloads:** msfconsole, social engineering toolkit
- **Analysis:** Burp Suite, metasploit, custom agents

-----

## 📦 Repositories

### 🔴 Core Projects

#### **[Local-Model](https://github.com/XenoCoreGiger31/Local-Model)**

**PenMaster Security — Autonomous Penetration Testing Agent**

An autonomous agent for coordinated, intelligent penetration testing. Runs Qwen 2.5-14B locally via LM Studio, orchestrates 17 security tools via MCP server, maintains persistent memory, and generates auditable pentest reports.

**Key Features:**

- Autonomous tool orchestration (masscan → nmap → exploit chain)
- Persistent negative experience cache (prevents redundant attempts)
- JSONL-backed short-term memory for decision tracking
- HTML pentest report generation
- Social engineering toolkit expansion
- Tested against Metasploitable (14/24 ports breached)

**Stack:** Python, Flask, Qwen 2.5-14B, LM Studio, MCP, Kali Linux

-----

#### **[Qwen-2.5-1.5B-Android](https://github.com/XenoCoreGiger31/Qwen-2.5-1.5B-Android)**

**Mobile Security Model for Android**

Quantized Qwen 2.5-1.5B model optimized for Android devices. Enables on-device inference for security assessments without cloud dependency.

**What’s Inside:**

- Multiple quantization formats (Q8 GGUF, Q4 GGUF, SafeTensors)
- Tested on Android 12+
- Low-latency inference
- Privacy-first (all processing local)

**Perfect for:** Security researchers, penetration testers, red teamers needing portable threat modeling

-----

#### **[Qwen-2.5-1.5B-Local-Uncensored](https://github.com/XenoCoreGiger31/Qwen-2.5-1.5B-Local-Uncensored)**

**Mobile Security Model for iOS**

Quantized Qwen 2.5-1.5B model for iOS devices. Run security assessments directly on iPhone/iPad without internet.

**What’s Inside:**

- Q8 GGUF, Q4 GGUF, SafeTensors formats
- iOS 15+ compatible
- Optimized for Off Grid app + local ML frameworks
- 341 downloads in first 24 hours

**Use Cases:** On-device vulnerability analysis, offline threat assessment, penetration testing workflows

-----

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=XenoCoreGiger31&show_icons=true&theme=tokyonight&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=XenoCoreGiger31&layout=compact&theme=tokyonight)

-----

## 🌐 Hugging Face Profile

I publish quantized models, Spaces, and security datasets on **[Hugging Face: automajicly](https://huggingface.co/automajicly)**

**Published:**

- **Qwen 2.5-1.5B quantized variants** (Q8 GGUF, Q4 GGUF, SafeTensors)
- **iOS/Android Spaces** with Gradio demos
- **Security model** (coming soon)

Check out the profile for model cards, download links, and integration guides.

-----

## 💬 Let’s Collaborate

I’m actively looking for collaborators on:

- **Autonomous agent improvements** (better tool selection, exploit chains)
- **Model optimization** (quantization, inference speed)
- **Security tooling** (new exploits, recon modules)
- **Mobile deployment** (iOS/Android frameworks, edge inference)
- **Open-source security projects**

**Interested?** Reach out below.

-----

## 📬 Get in Touch

- **Email:** [your.email@here.com](mailto:christopherwsheridan@gmailcom)
- **GitHub:** [@XenoCoreGiger31](https://github.com/XenoCoreGiger31)
- **Hugging Face:** [@automajicly](https://huggingface.co/automajicly)
- **GitHub Sponsors:** [Support the work](https://github.com/sponsors/XenoCoreGiger31)

-----

## 🎯 Current Focus (2026)

- ✅ Autonomous agent infrastructure (V1 complete)
- 🔄 Traceability system (requirements → decisions → implementation)
- 🚧 Swarm agent architecture (multi-agent coordination)
- 📱 Expanded mobile model suite
- 🔐 Advanced social engineering toolkit

-----

## 📚 Learning & Growth

I’m self-taught and constantly building in public. If you see something interesting (or broken), let me know. I believe in:

- **Learning by building** — real tools, real problems
- **Public development** — all work on GitHub, all reasoning documented
- **Security research** — rigorous testing, transparent findings
- **Open collaboration** — no gatekeeping, knowledge shared

-----

**Last updated:** June 2026 | Always building | No AI-generated BS 🚀
