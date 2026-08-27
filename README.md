# Robin Stahlbaum

**Senior Site Reliability Engineer · Apple Platform Developer**
Mississauga, ON &nbsp;·&nbsp; 416-624-9881 &nbsp;·&nbsp; rstahlb@gmail.com &nbsp;·&nbsp; [Resume (PDF)](https://github.com/user-attachments/files/31532148/Robin_Stahlbaum_Resume.pdf)

**Open to opportunities in:** Site Reliability Engineering / infrastructure roles, and native product development for Mac and iPad.

20+ years architecting and hardening enterprise Linux infrastructure — from PCI-compliant banking systems at Scotiabank to global content-delivery platforms at Bell. Alongside that career, I've built an independent portfolio of native macOS and iPadOS applications in Swift, spanning graphics engines, on-device AI, and systems-level tooling. Open to roles on either side of that experience: enterprise SRE/infrastructure, or hands-on Apple platform development.

---

## Professional Experience (20+ Years, SRE & Infrastructure)

- **Infrastructure & Linux Administrator — Total Cyber Solution:** Architected multi-agent orchestration systems, engineered C++ graphics/render pipelines bridged via Objective-C++ to native Swift threads, and built automated CVE/CISA compliance tracking services.
- **Linux Administrator / SRE — Bell Media & Bell Canada:** Supported global high-traffic content distribution on Akamai CDN, built and maintained RHEL environments on VMware/OpenStack at scale, and automated system configuration with Ansible.
- **Senior Linux Administrator — Scotiabank:** Provisioned and hardened PCI-compliant financial environments on VMware vSphere, managed application servers for global wealth management platforms, and built secure bastion/jump-box access using SSH ProxyJump.
- **Escalation & Support Engineer — VMware, Microsoft:** Resolved core hypervisor kernel defects, managed high-severity production incidents from open to close, and diagnosed complex OS-level performance issues for enterprise deployments.

Full role-by-role history, including Bell Canada, Route1, Symcor, and Scotiabank, is available in the [resume](https://github.com/user-attachments/files/31532148/Robin_Stahlbaum_Resume.pdf).

---

## Current Focus

- **Systems:** Linux (RHEL/Ubuntu) administration, VMware vSphere
- **Apple Platforms:** Swift, SwiftUI, Apple Silicon (M1 Max, M4)
- **Applied AI:** On-device multi-agent orchestration, local model fine-tuning (PyTorch, Apple MLX)
- **Security Tooling:** Bastion/jump-host architecture, CISA KEV remediation automation

---

## Project Portfolio — Native Apple Applications (Swift)

Independent projects built in Swift for macOS and iPadOS/iOS, covering graphics engines, on-device AI, and systems-level integrations. Demo recordings linked below.

| # | Project | Description | Demo |
|---|---------|-------------|------|
| 1 | **SecWatch** — Cybersecurity & Compliance Dashboard | Multi-pane SwiftUI/WidgetKit app parsing live CVE feeds and tracking infrastructure exposure against the CISA Known Exploited Vulnerabilities (KEV) catalog, with automated alert escalation. | [Watch](https://github.com/user-attachments/assets/386503a3-2cbb-4ca7-8b3b-020db119dd40) |
| 2 | **Multi-Agent Router & Local Fine-Tuning Pipeline** | Orchestration framework using a judgment-parsing model (Llama 3) to evaluate prompt intent and route tasks to specialized downstream models (Qwen 2.5 Coder), with local state persistence. | — |
| 3 | **3D Graphics Engine — Metal Raytracing Viewport** | Standalone Swift/Apple Metal graphics runtime supporting multi-threaded, real-time 4K raytraced viewport rendering. Jolt Physics integration for rigid-body dynamics in progress. | [Watch](https://github.com/user-attachments/assets/42ee6339-60e6-49d0-82a3-fda448a58148) |
| 4 | **3D Graphics Engine — Physics Bridge** | Objective-C++ bridge layer connecting a C++ physics engine to native Swift rendering threads, enabling real-time deformable-body simulation. | [Watch](https://github.com/user-attachments/assets/1e1f7235-7c1e-4b84-935f-c9f72ad5e948) |
| 5 | **3D Graphics Engine — Custom Sculpting UI** | Fully custom Swift user-interface layer built for a ZBrush-style 3D sculpting tool prototype. | [Watch](https://github.com/user-attachments/assets/04adaca5-dc03-4874-9f2d-00f68888ffb0) |
| 6 | **Cross-Platform Clipboard Manager** | Low-level `UIPasteboard` interception combined with Apple's `UTType` framework to capture and cache multi-format clipboard data (text, images, URLs) into CoreData. | [Watch](https://github.com/user-attachments/assets/bc62b107-bf53-4de4-80d2-01eabcbb20f2) |
| 7 | **Custom Markdown Parsing Engine** | Native lexical scanner parsing Markdown into structured Abstract Syntax Trees using TextKit 2, with secure document-provider handling and cross-platform drag-and-drop support. | [Watch](https://github.com/user-attachments/assets/cc4f6ad6-f765-4759-919b-6db680546210) |
| 8 | **Interactive Touch Canvas for Kids** | High-precision, low-latency vector-drawing app built with PencilKit, with native palm-rejection support. | [Watch](https://github.com/user-attachments/assets/f8b6be35-3f8f-4c80-8f4d-8b81f653e5f6) |
| 9 | **Shared Canvas — PencilKit + Skia** | Prototype cross-engine drawing canvas combining Apple PencilKit with Google's Skia rendering engine. | [Watch](https://github.com/user-attachments/assets/c5c36cb8-082e-45ff-b8d8-3b5daf3aec63) |
| 10 | **macOS Widget — WebView-Wrapped** | Native macOS widget using IOKit for system-level battery/power monitoring, with a WebView-wrapped UI for rapid theme iteration and custom audio alerts. | [Watch](https://github.com/user-attachments/assets/1b9f7fb6-6336-4cba-ba05-880b4f522f6a) |
| 11 | **Go-Game Analyzer** | iPadOS/iOS app that loads saved Go game records and uses an on-device local LLM to generate a natural-language game summary. | [Watch](https://github.com/user-attachments/assets/34fe935a-5dab-40f6-8e2c-7411af299146) |
| 12 | **Zoomy — Screen Magnifier** | Swift-based screen magnification accessibility utility for macOS/iOS. | [Watch](https://github.com/user-attachments/assets/5425b63e-d1ab-4214-9de3-11c4326fc382) |
| 13 | **iPad Local LLM Port (M4)** | Ported and optimized a quantized mixture-of-experts language model (Gemma) to run locally on iPad M4 hardware within tight on-device memory constraints. | [Watch](https://github.com/user-attachments/assets/251144dd-c00f-48ee-9069-752d551a56fd) |
| 14 | **Guitar Practice App** | iPadOS/iOS app for slowing down audio tracks (MP3/WAV) for practice, with custom loop markers, a looper, and an EQ section built on Apple's audio frameworks. | [Watch](https://github.com/user-attachments/assets/b4a137e7-c349-43ee-805a-091647b30b4a) |

---

## Technical Skills

**Core Infrastructure & Systems Programming**
Linux (RHEL, Ubuntu, legacy Solaris 11 — 20+ years production administration) · Swift (Advanced Concurrency, Generics) · Modern C++ (C++17/20) · Objective-C++ · Python (PyTorch) · Bash · VMware ESX/vSphere · OpenStack · QEMU/KVM · LVM · SAN

**Edge AI & Machine Learning**
Multi-Agent Orchestration (MoA) · Semantic query routing · LoRA fine-tuning · RLHF alignment · GGUF quantization · Apple MLX

**Apple SDK Frameworks**
RealityKit & ARKit · WidgetKit · CoreData · TextKit 2 · PencilKit

---

*Robin Stahlbaum · [Resume](https://github.com/user-attachments/files/31532148/Robin_Stahlbaum_Resume.pdf) · rstahlb@gmail.com*
