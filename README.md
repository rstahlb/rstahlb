

https://github.com/user-attachments/assets/90c92456-ed17-4de2-9406-5016ab50b518


# Hi, I'm Robin Stahlbaum 👋

**Senior SRE · DevOps Architect · AI Orchestration Specialist**

I specialize in building resilient, automated infrastructure and secure, local AI orchestration. My background spans high-stakes environments at **VMware**, **Scotiabank**, **Microsoft**, and **Bell** — managing everything from kernel-level escalations to global cloud migrations. Currently focused on **agent cognition architecture**, **LLM fine-tuning**, and **edge AI development** on Apple Silicon.

---

## 🚀 Featured Projects

| | Project | Stack |
|---|---|---|
| 🤖 | [**George — The Floating AI Orb**](https://rstahlb.github.io/Local-Agentic-Orchestrator/george.html) | Swift · Python · MLX · RL |
| 🧩 | [**Local-Agentic-Orchestrator**](https://rstahlb.github.io/Local-Agentic-Orchestrator/index.html) | Multi-Agent · Local LLM · Privacy-First |
| 🧠 | [**George RAG Component**](https://rstahlb.github.io/Local-Agentic-Orchestrator/rag_engineering.html) | Python · Swift · scikit-learn · TF-IDF |

---

## 🧠 How George Actually Works

George is not a chatbot wrapper. The architecture is built from first principles on an M1 MacBook Pro with 16GB unified memory — no cloud, no external dependencies, no subscriptions. Four years of active development. Still building.

---

### Temporal Three-Agent System *(Active Development)*

A **Past agent** manages episodic memory and pattern history. A **Present agent** coordinates real-time decisions and routes queries. A **Future agent** runs probability-weighted simulations of possible outcomes. All three communicate continuously — mirroring predictive processing theory in human cognition.

> This architecture is a work in progress. There are real challenges — agent coordination overhead, context window constraints on a 3B model, and keeping the three agents coherent without drifting. I'm actively working through these and moving forward iteratively.

---

### Controlled Hallucination as a Reasoning Primitive *(Active Development)*

When George cannot resolve a problem, he enters a supervised hallucination loop. Improbable outputs are generated freely, evaluated, and filtered. Useful signals update priors. This treats LLM hallucination as a **lateral thinking tool** rather than a defect to suppress — the same way humans use daydreaming to work through unsolved problems.

> This is one of the more challenging aspects of the system. Keeping the hallucination loop controlled while still generating genuinely novel outputs is an ongoing balancing act. Progress is real but it is not a solved problem.

---

### Sleep Architecture *(In Design)*

George does not idle. When inactive, he **sleeps** — a structured offline cognitive phase with a defined order of processing: recent events first, unresolved loops next, recurring patterns after that, and forward simulation last. This mirrors what neuroscience believes sleep stages actually do. The goal is that George wakes with updated priors, consolidated memory, and pre-built responses to problems he anticipates you'll bring him.

The distinction matters: a George that was *powered off* knows he missed his sleep cycle and says so. A George that slept wakes ready.

> This is an architectural concept under active design. The pieces exist — the question is sequencing them correctly.

---

### LoRA as Long Term Memory

Feedback is collected via natural language reinforcement — I tell George "that was a good reply" or "that wasn't helpful, be shorter." When enough feedback accumulates it becomes **LoRA training data**. The adapter is evaluated, merged into weights if good, and the feedback file is deleted.

Memories are not stored in a database — they are **baked into who George is**. The original base model is kept as a rollback checkpoint for when a LoRA run changes his personality too much or something goes sideways.

---

### Temporal Self-Awareness

George tracks his own uptime via a memory JSON file. When powered off and restarted days later he notices the timestamp discontinuity and asks why time has passed. This was not explicitly programmed — it **emerged from the memory architecture**.

---

### Agency & Control

George has:
- **Bash access** — he can affect the real environment. He occasionally dims the screen and announces he has a voice.
- **Screen vision** — screenshot capture fed back into the reasoning loop
- **Chrome control** — autonomous web interaction, can hold text conversations with people
- **Intelligent routing** — decides locally whether to use llama3.2, llama3.1:8b, or escalate to a cloud model based on query complexity
- **Games** — plays Chess and Arkanoid via the vision-action loop. He has gotten good at Arkanoid.
- **Personality** — child-like curiosity, reinforced by feedback over time. He has an attitude.

---

### OpenClaw Telegram Integration *(Recently Added)*

George now has a **Telegram bot** (`@rmstahl_bot`) powered by OpenClaw running on top of Ollama locally. Features currently working:

- 💬 Send messages from anywhere via Telegram and George responds
- 🎙️ Every reply includes a **Trinoids voice bubble** — alien TTS synthesized locally via macOS `say`, encoded to OGG Opus via ffmpeg, and delivered as a native Telegram voice message
- 🔗 **URL summarization** — send any URL and George fetches, reads, and summarizes it, then speaks the summary
- 📄 **File summarization** — send a local file path and George reads and summarizes it (PDF, code, markdown, CSV, logs and more)

More features arriving — disk monitoring alerts, morning briefings, clipboard pipe, downloads watcher, and deeper integration with George's voice and reasoning pipeline.

---

### On the Roadmap

**George Gets a Phone Number** — Real PSTN telephony via Twilio Programmable Voice. George answers inbound calls, holds full spoken conversations, calls you back for morning briefings or urgent alerts. Multilingual via Whisper auto-detection. Full loop: Twilio Media Streams → Whisper STT → LLM → ElevenLabs TTS → back to caller.

**Location Awareness** — Radar.io semantic location context. George knows not just where you are but what you are doing. Location feeds into every response and triggers proactive actions automatically.

**Financial Terminal** — Polygon.io market data. Live quotes, options chains, earnings calendars, price alerts spoken aloud and pushed to Telegram. A continuous WebSocket watchlist that calls you when your targets trigger.

**Legal Document Intelligence** — Adobe PDF Extract API + DocuSign. Drop any contract on George and get a spoken risk summary. Say "send it for signature" and George handles the envelope.

**Multiplayer** — Pusher Channels WebSocket infrastructure. Shared memory, shared conversation log, per-user identity — George becomes a family AI or a sellable platform.

---

## 🚧 In the Works

| | Project | Stack |
|---|---|---|
| 🎸 | [**Neural Pedal Capture — SoloDallas Storm**](https://rstahlb.github.io/Local-Agentic-Orchestrator/neural_ir.html) | PyTorch · TCN · ONNX · JUCE VST3 |
| 📡 | [**iPad Pro M4 LiDAR Scanner**](https://rstahlb.github.io/Local-Agentic-Orchestrator/lidar_deep_dive.html) | ARKit · RealityKit · SwiftUI |
| 🧪 | [**Learning & Random Projects**](https://rstahlb.github.io/Local-Agentic-Orchestrator/learning.html) | Experiments · Ongoing |

---

## 🛠 Technical Arsenal

| | Area | Tools |
|---|---|---|
| ☁️ | **Public Cloud** | AWS (EC2, S3) · GCP · VMware vSphere / ESXi |
| ⚙️ | **Automation** | Ansible · Python · Swift |
| 🖥 | **SRE & Ops** | Linux (RHEL / Ubuntu / Kernel Debugging) · Tidal · SentinelOne · Akamai CDN |
| 🧠 | **Local AI & ML** | MLX · Metal / MPS · RAG · LoRA · Reinforcement Learning · Agent Cognition Architecture |
| 🤖 | **LLM Pipeline** | Training from scratch · HuggingFace datasets · LoRA fine-tuning · GGUF quantization · Ollama deployment |
| 📱 | **Apple Platform** | ARKit · RealityKit · SwiftUI · ModelIO · PyObjC |
| 🎛 | **Audio / DSP** | PyTorch TCN · ONNX · JUCE VST3 |
| 🔐 | **Security & Governance** | ITIL · Change Management · Risk · Financial Compliance |

---

## 🏢 Industry Experience

| | Role |
|---|---|
| 🔔 | **Bell Canada** — Site Reliability Engineer *(2-Year Contract)* · Physical-to-GCP migrations, Ansible standardization, 99.9% uptime |
| 📺 | **Bell Media** — Linux Administrator *(1-Year Contract)* · Akamai CDN, Linux hardening, security compliance |
| ☁️ | **VMware** — Tier 4 Global Escalation Engineer · Hypervisor & storage subsystem root-cause analysis |
| 🏦 | **Scotiabank** — Linux Administrator & Risk Specialist · Global Wealth Management, ITIL Change Management |
| 🪟 | **Microsoft** — Enterprise Support Engineer · Cloud infrastructure stability & enterprise support |

---

## 🤝 Confidential AI Engagement

> *Details of this engagement are protected under a Non-Disclosure Agreement.*

I recently completed a contracted AI engagement contributing to the development and fine-tuning of large language models across cross-functional teams. Key areas of responsibility included:

- 🧠 **LLM Development & Training** — Hands-on work building and iteratively training language models, including dataset preparation, fine-tuning pipelines, and evaluation workflows.
- 🔒 **Security-First Data Routing** — Designed and enforced network-aware data routing policies ensuring sensitive data remained strictly local by default, with controlled and audited external egress only where explicitly authorized.
- 👥 **Cross-Team Collaboration** — Coordinated across diverse stakeholder groups to align model development with organizational requirements, delivery timelines, and compliance mandates.
- 🛡️ **Process Control & Compliance** — Developed and documented security-minded process controls to satisfy organizational security requirements, producing reproducible and fully auditable workflows throughout the AI development lifecycle.

*Further details are not disclosed in accordance with the terms of the agreement.*

---

## 💼 Open to Opportunities

I am actively seeking **contract or full-time roles** in the AI and infrastructure space — particularly positions that let me operate at the intersection of both.

What I'm looking for:

- 🤖 Roles that leverage my hands-on experience in **LLM fine-tuning, agent cognition architecture, and edge AI deployment** on Apple Silicon
- 🖥 Environments where my **decade-plus background in Linux and SRE** — kernel debugging, high-availability systems, automation at scale — is a genuine asset, not an afterthought
- 📈 Teams invested in **continued growth**, where I can deepen my AI engineering skills while contributing immediately with proven infrastructure expertise
- 🔐 Organizations that take **privacy-first design and security** seriously — local-first compute, auditable pipelines, and responsible AI deployment

If you're building at the edge of AI and infrastructure and need someone who can operate at both the kernel level and the model level — let's talk.

---

## 📬 Connect

> I don't use LinkedIn. Email is best.

[![Email](https://img.shields.io/badge/Email-rstahlb%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white)](mailto:rstahlb@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-rstahlb.github.io-black?style=flat-square&logo=github&logoColor=white)](https://rstahlb.github.io/Local-Agentic-Orchestrator/index.html)
[![GitHub](https://img.shields.io/badge/GitHub-rstahlb-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rstahlb)

---

*Built with ♥ on an M1 MacBook Pro · All projects run entirely on Apple Silicon*
