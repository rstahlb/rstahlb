<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About — Robin Stahlbaum</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Geist+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: #ffffff;
    color: #1a1a1a;
    font-family: 'Inter', sans-serif;
    font-size: 15px;
    line-height: 1.8;
    max-width: 720px;
    margin: 0 auto;
    padding: 3rem 2rem 5rem;
    -webkit-font-smoothing: antialiased;
  }

  /* HEADER */
  .name {
    font-size: 1.6rem;
    font-weight: 700;
    letter-spacing: -0.02em;
    color: #111;
    margin-bottom: 0.15rem;
  }
  .title {
    font-size: 0.85rem;
    color: #888;
    font-weight: 400;
    margin-bottom: 1.5rem;
    font-family: 'Geist Mono', monospace;
    letter-spacing: 0.02em;
  }
  .bio {
    font-size: 0.92rem;
    color: #444;
    line-height: 1.85;
    margin-bottom: 2.25rem;
  }
  .bio strong { color: #111; font-weight: 600; }

  /* DIVIDER */
  hr {
    border: none;
    border-top: 1px solid #e5e5e5;
    margin: 2rem 0;
  }

  /* SECTION LABELS */
  .section-label {
    font-family: 'Geist Mono', monospace;
    font-size: 0.65rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: #bbb;
    margin-bottom: 1rem;
  }

  /* LINK ROWS — the core format */
  .link-group { margin-bottom: 2rem; }
  .link-group + .link-group { margin-top: 0.25rem; }

  .link-item {
    display: flex;
    align-items: flex-start;
    gap: 0.85rem;
    padding: 0.6rem 0;
    border-bottom: 1px solid #f0f0f0;
    text-decoration: none;
    color: inherit;
    transition: background 0.15s;
  }
  .link-item:last-child { border-bottom: none; }
  .link-item:hover .item-title { color: #0066ff; }

  .item-icon {
    font-size: 1.1rem;
    width: 1.6rem;
    flex-shrink: 0;
    text-align: center;
    margin-top: 0.05rem;
  }

  /* SVG icons for places without emoji */
  .item-icon svg {
    width: 18px;
    height: 18px;
    vertical-align: middle;
    opacity: 0.55;
  }

  .item-body { flex: 1; }
  .item-title {
    font-size: 0.9rem;
    font-weight: 600;
    color: #111;
    line-height: 1.4;
  }
  .item-meta {
    font-size: 0.78rem;
    color: #888;
    margin-top: 0.15rem;
    line-height: 1.5;
  }
  .item-tag {
    display: inline-block;
    font-family: 'Geist Mono', monospace;
    font-size: 0.62rem;
    letter-spacing: 0.08em;
    color: #aaa;
    margin-top: 0.2rem;
  }
  .wip .item-title::after {
    content: ' — WIP';
    font-weight: 400;
    color: #bbb;
    font-size: 0.75rem;
  }

  /* CONNECT BUTTONS */
  .connect-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin-top: 0.75rem;
  }
  .connect-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    font-family: 'Geist Mono', monospace;
    font-size: 0.75rem;
    color: #555;
    border: 1px solid #ddd;
    border-radius: 6px;
    padding: 0.4rem 0.9rem;
    text-decoration: none;
    transition: color 0.2s, border-color 0.2s;
  }
  .connect-btn:hover { color: #0066ff; border-color: #0066ff; }
  .connect-btn svg {
    width: 13px; height: 13px; flex-shrink: 0;
    opacity: 0.6;
  }

  /* FOOTER */
  .footer {
    margin-top: 3rem;
    font-size: 0.75rem;
    color: #ccc;
    font-family: 'Geist Mono', monospace;
  }
  .footer a { color: #aaa; text-decoration: none; }
  .footer a:hover { color: #0066ff; }
</style>
</head>
<body>

<!-- ── HEADER ── -->
<p class="name">Robin Stahlbaum 👋</p>
<p class="title">Senior SRE · DevOps Architect · AI Orchestration Specialist</p>

<p class="bio">
  I specialize in building resilient, automated infrastructure and secure, local AI orchestration.
  My background spans high-stakes environments at <strong>VMware</strong>, <strong>Scotiabank</strong>,
  <strong>Microsoft</strong>, and <strong>Bell</strong> — managing everything from kernel-level escalations
  to global cloud migrations. Currently focused on <strong>fine-tuning LLMs</strong> and
  <strong>edge AI development</strong> on Apple Silicon.
</p>

<hr>

<!-- ── FEATURED PROJECTS ── -->
<p class="section-label">🚀 Featured Projects</p>

<div class="link-group">

  <a class="link-item" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/george.html">
    <span class="item-icon">🤖</span>
    <div class="item-body">
      <div class="item-title">George — The Floating AI Orb (macOS)</div>
      <div class="item-meta">Voice-first, privacy-focused AI companion built natively in Swift + Python. Hybrid compute: local MLX with cloud fallback. Includes a reinforcement learning Arkanoid agent and a Chess engine.</div>
      <span class="item-tag">Swift · Python · MLX · Reinforcement Learning →</span>
    </div>
  </a>

  <a class="link-item" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/index.html">
    <span class="item-icon">🧩</span>
    <div class="item-body">
      <div class="item-title">Local-Agentic-Orchestrator</div>
      <div class="item-meta">Modular, privacy-first multi-agent AI framework for 100% local execution. Autonomous system administration using local LLMs, private RAG, and hardware-optimized fine-tuning on Apple Silicon.</div>
      <span class="item-tag">Multi-Agent · Local LLM · Privacy-First →</span>
    </div>
  </a>

  <a class="link-item" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/rag_engineering.html">
    <span class="item-icon">🧬</span>
    <div class="item-body">
      <div class="item-title">Private Document Analysis — Local RAG</div>
      <div class="item-meta">Secure, on-premise knowledge retrieval. TF-IDF RAG pipeline replacing a 6,000-char static context dump with targeted retrieval. 35 tests · 100% accuracy · 0.98ms latency.</div>
      <span class="item-tag">Python · scikit-learn · Swift →</span>
    </div>
  </a>

  <a class="link-item" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/gpt.html">
    <span class="item-icon">🧠</span>
    <div class="item-body">
      <div class="item-title">GPT Architecture from Scratch</div>
      <div class="item-meta">Ground-up GPT transformer implementation — self-attention, cross-entropy loss, backpropagation. Custom BPE tokenizer, full training pipeline, and LoRA fine-tuning entirely on M1 unified memory.</div>
      <span class="item-tag">PyTorch · Flask · Apple Silicon · LoRA →</span>
    </div>
  </a>

  <a class="link-item" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/llm_guide.html">
    <span class="item-icon">🤗</span>
    <div class="item-body">
      <div class="item-title">Fine-Tuning LLMs on Apple Silicon — Guide</div>
      <div class="item-meta">Complete hardware-optimization guide for MLX and unified memory. LoRA fine-tuning, validation, and deploying a custom model in Ollama. Zero cloud compute required.</div>
      <span class="item-tag">MLX · LoRA · Ollama · M1 →</span>
    </div>
  </a>

</div>

<hr>

<!-- ── PROJECTS IN THE WORKS ── -->
<p class="section-label">🚧 In the Works</p>

<div class="link-group">

  <a class="link-item wip" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/neural_ir.html">
    <span class="item-icon">🎸</span>
    <div class="item-body">
      <div class="item-title">Neural Pedal Capture — SoloDallas Storm</div>
      <div class="item-meta">Capturing analog soul through Temporal Convolutional Networks (TCN). 27-point physical measurement plan, trained in PyTorch, exported via ONNX, deployed as a cross-platform VST3 plugin using JUCE.</div>
      <span class="item-tag">PyTorch · TCN · ONNX · JUCE VST3 →</span>
    </div>
  </a>

  <a class="link-item wip" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/lidar_deep_dive.html">
    <span class="item-icon">📡</span>
    <div class="item-body">
      <div class="item-title">iPad Pro M4 LiDAR Scanner</div>
      <div class="item-meta">High-fidelity 3D mesh generation using M4 hardware-accelerated ray tracing. ARKit + RealityKit for raw laser depth capture. Full-stack SwiftUI app with USDZ / OBJ export. Optimized for the 16GB M4 iPad Pro.</div>
      <span class="item-tag">ARKit · RealityKit · SwiftUI · ModelIO →</span>
    </div>
  </a>

</div>

<hr>

<!-- ── TECHNICAL ARSENAL ── -->
<p class="section-label">🛠 Technical Arsenal</p>

<div class="link-group">

  <div class="link-item">
    <span class="item-icon">
      <!-- Cloud icon -->
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M18 10h-1.26A8 8 0 1 0 9 20h9a5 5 0 0 0 0-10z"/></svg>
    </span>
    <div class="item-body">
      <div class="item-title">Public Cloud</div>
      <div class="item-meta">AWS (EC2, S3) · GCP (Physical-to-Cloud Migration) · VMware vSphere / ESXi</div>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">
      <!-- Terminal icon -->
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><polyline points="4 17 10 11 4 5"/><line x1="12" y1="19" x2="20" y2="19"/></svg>
    </span>
    <div class="item-body">
      <div class="item-title">Automation</div>
      <div class="item-meta">Ansible (Playbooks / Roles) · Python (Custom tooling) · Swift (macOS Native)</div>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">
      <!-- Server icon -->
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="8" rx="2" ry="2"/><rect x="2" y="14" width="20" height="8" rx="2" ry="2"/><line x1="6" y1="6" x2="6.01" y2="6"/><line x1="6" y1="18" x2="6.01" y2="18"/></svg>
    </span>
    <div class="item-body">
      <div class="item-title">SRE &amp; Ops</div>
      <div class="item-meta">Linux (RHEL / Ubuntu / Kernel Debugging) · Tidal Enterprise Scheduler · SentinelOne Performance Tuning · Akamai CDN</div>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">
      <!-- CPU / chip icon -->
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="6" height="6"/><rect x="2" y="2" width="20" height="20" rx="2" ry="2"/><line x1="9" y1="2" x2="9" y2="9"/><line x1="15" y1="2" x2="15" y2="9"/><line x1="9" y1="15" x2="9" y2="22"/><line x1="15" y1="15" x2="15" y2="22"/><line x1="2" y1="9" x2="9" y2="9"/><line x1="2" y1="15" x2="9" y2="15"/><line x1="15" y1="9" x2="22" y2="9"/><line x1="15" y1="15" x2="22" y2="15"/></svg>
    </span>
    <div class="item-body">
      <div class="item-title">Local AI &amp; ML</div>
      <div class="item-meta">Reinforcement Learning · MLX Framework · Metal Performance Shaders (MPS) · RAG Engineering · LoRA Fine-Tuning</div>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">
      <!-- Shield icon -->
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
    </span>
    <div class="item-body">
      <div class="item-title">Security &amp; Governance</div>
      <div class="item-meta">Change Management (ITIL) · Risk Management · Financial Compliance · Secure Linux Environments</div>
    </div>
  </div>

</div>

<hr>

<!-- ── INDUSTRY EXPERIENCE ── -->
<p class="section-label">🏢 Industry Experience</p>

<div class="link-group">

  <div class="link-item">
    <span class="item-icon">🔔</span>
    <div class="item-body">
      <div class="item-title">Bell Canada — Site Reliability Engineer</div>
      <div class="item-meta">Physical-to-GCP migrations, 99.9% uptime, Ansible environment standardization, new-hire training, and third-party vendor coordination for security compliance on Bell-hosted infrastructure.</div>
      <span class="item-tag">GCP · Ansible · SRE · 2-Year Contract</span>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">📺</span>
    <div class="item-body">
      <div class="item-title">Bell Media — Linux Administrator</div>
      <div class="item-meta">Akamai CDN management for Bell Media news properties. Linux hardening, security compliance, and Confluence SOP authoring for onboarding and offshore teams.</div>
      <span class="item-tag">Akamai · Linux · CDN · 1-Year Contract</span>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">☁️</span>
    <div class="item-body">
      <div class="item-title">VMware — Tier 4 Global Escalation Engineer</div>
      <div class="item-meta">Root-cause analysis on critical hypervisor and storage subsystem outages across enterprise environments worldwide. The highest tier of technical escalation support.</div>
      <span class="item-tag">ESXi · vSphere · Kernel Debugging · Global Escalations</span>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">🏦</span>
    <div class="item-body">
      <div class="item-title">Scotiabank — Linux Administrator &amp; Risk Specialist</div>
      <div class="item-meta">Secure Linux environments for Global Wealth Management. Active Change Management team member — approving high-risk production deployments under strict financial compliance protocols.</div>
      <span class="item-tag">Linux · ITIL · Risk Management · Global Wealth</span>
    </div>
  </div>

  <div class="link-item">
    <span class="item-icon">🪟</span>
    <div class="item-body">
      <div class="item-title">Microsoft — Enterprise Support Engineer</div>
      <div class="item-meta">Cloud infrastructure stability and enterprise support, ensuring production reliability for large-scale Microsoft cloud deployments.</div>
      <span class="item-tag">Azure · Cloud Infrastructure · Enterprise Support</span>
    </div>
  </div>

</div>

<hr>

<!-- ── CONNECT ── -->
<p class="section-label">📬 Get in Touch</p>
<p style="font-size:0.88rem;color:#666;margin-bottom:0.85rem;">I don't use LinkedIn. Email is best.</p>

<div class="connect-row">
  <a class="connect-btn" href="mailto:rstahlb@gmail.com">
    <!-- Mail icon -->
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
    rstahlb@gmail.com
  </a>
  <a class="connect-btn" href="https://github.com/rstahlb" target="_blank">
    <!-- GitHub icon -->
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>
    github.com/rstahlb ↗
  </a>
  <a class="connect-btn" href="https://rstahlb.github.io/Local-Agentic-Orchestrator/index.html">
    <!-- Portfolio / grid icon -->
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="7" height="7"/><rect x="14" y="3" width="7" height="7"/><rect x="14" y="14" width="7" height="7"/><rect x="3" y="14" width="7" height="7"/></svg>
    Portfolio ↗
  </a>
</div>

<div class="footer" style="margin-top:3rem;">
  Built with ♥ on an M1 MacBook Pro &nbsp;·&nbsp; All projects run entirely on Apple Silicon &nbsp;·&nbsp;
  <a href="https://rstahlb.github.io/Local-Agentic-Orchestrator/index.html">← Back to Portfolio</a>
</div>

</body>
</html>
