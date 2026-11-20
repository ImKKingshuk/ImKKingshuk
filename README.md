# ImKKingshuk

**Researcher & Software Engineer**

I research the security of machine learning systems: how much a deployed model
gives away through its API, and how agentic AI can be defended against attacks
that arrive through the tools it uses.

I came to research through engineering. I've built production systems and
open-source tools for security research and automation, and that shapes how I
work: I look for attacks and defenses that hold up against real deployments,
and I build the experiments, tooling, and reproducible code behind every
result. I work mainly in **Python, Rust, and TypeScript**.

[Website](https://ki.ngsh.uk) · [ORCID](https://orcid.org/0009-0003-8222-6088) ·
[LinkedIn](https://www.linkedin.com/in/imkkingshuk) · [X](https://x.com/ImKKingshuk)

## Publications

- **Recovery Boundaries and Quantization Limits for Low-Rank Neural Adaptations under Restricted Oracles** \
  Indocrypt 2026 (Springer LNCS) · accepted ·
  [paper](https://github.com/ImKKingshuk/IndoCrypt2026-LoRA-RBQL/blob/main/paper/main.pdf) ·
  [code](https://github.com/ImKKingshuk/IndoCrypt2026-LoRA-RBQL) \
  When a LoRA adapter sits on a public base model, which prediction APIs let an
  attacker recover it exactly, and when does score quantization actually protect it.

- **ShieldAgent: Defense-in-Depth Security Framework for Agentic AI Tool Use** \
  IEEE CONECCT 2026 · accepted ·
  [code](https://github.com/ImKKingshuk/ShieldAgent-IEEE-CONECCT-2026) \
  Layered defenses against indirect prompt injection and tool-chain attacks on
  tool-using agents: response sanitization, intent verification, anomaly
  detection over tool sequences, and sandboxed execution.

## Research interests

- **Machine learning security** — model extraction, what prediction APIs leak,
  and which output defenses hold against an adaptive attacker.
- **Agentic AI security** — indirect prompt injection, tool-chain attacks,
  execution isolation, and defense in depth for tool-using agents.
- **Cryptography & cryptanalysis** — protocol security, post-quantum
  cryptography, and practical attack/defense analysis.
- **Efficient AI systems** — sparse architectures, efficient inference, and ML
  on consumer hardware.

## Engineering

### [LockKnife](https://github.com/ImKKingshuk/LockKnife)

Android security research and forensics toolkit built around Python orchestration
with Rust-accelerated components.

### [USBoverSSH](https://github.com/ImKKingshuk/USBoverSSH)

Rust-based framework for securely tunneling and sharing USB devices over SSH.

### [BloatwareHatao](https://github.com/ImKKingshuk/BloatwareHatao)

Rust toolkit for Android package management, debloating, restoration, and
device optimization.

## Primary tools

**Languages** : Rust · Python · TypeScript · Bash · LaTeX

**ML & Research** : PyTorch · MLX · NumPy · Polars

**Backend & Data** : FastAPI · PostgreSQL · Redis · Hono

**Applications & Tooling** : Next.js · Tauri · Bun
