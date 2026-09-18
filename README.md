# David Coldeira

**Full-stack Python engineer · production systems end to end · LLMs where they can be verified**

Bristol, UK · EU citizen · ten years in software · physics graduate · Linux (Debian) user

I design, build and run production systems from scratch: architecture, backend,
frontend, deployment. When a language model goes into one of them, deterministic
code checks its output before it reaches a user or a database, and permissions
are enforced by the system rather than by the prompt.

---

## What I have shipped

**Gio — an AI assistant over a live laboratory database** · day job, Geoquip Marine
LLM tool-use inside [GQMLab](https://gqmlab.geoquip-marine.com), the LIMS I built
for a UKAS-accredited geotechnical laboratory. Natural-language SQL, charts and live
report-schema introspection on a read-only database user with query validation and
role-gated access. In production for the lab's engineers.
Stack: Python/Flask · Flutter · MySQL · Docker · nginx · Hetzner

**Marco — an LLM-powered passage planner** · [Forza7](https://forza7.dev) sailing suite
Reasons over live weather, tide and boat-performance data to propose offshore
routes. Every AI-generated waypoint is validated against real water and depth data
before the sailor sees it. Flutter apps on a FastAPI/PostgreSQL backend.

**Bell — a self-hosted fine-tuned physics assistant** · 2025
Qwen3-8B with a LoRA adapter trained on 815 instruction pairs, as a
provider-swappable alternative to a hosted LLM API. Sandboxed Python execution,
Docker/Caddy deployment, GDPR-compliant. Ran live at bell.entangledcode.dev; now
offline, code and training data kept. *Code on request.*

**Froe — a local-first coding agent in Go** · 2026
Built for data governance: source code never has to leave the machine, the LAN or
the EU. Local open-weight models are the default path, hosted providers are
optional adapters, and nothing about a model is compiled in. A single static Go
binary for the terminal and Neovim that runs on a 4 GB laptop. *Private repo,
available on request.*

---

## Writing

- [Putting an LLM on a Production Database, Read-Only by Construction](https://dcoldeira.github.io/posts/2026-09-16-llm-production-database/)
  Four independent layers, only one of which actually matters, and why the prompt is the layer you should trust least.
- [Don't Let the Model Do the Physics](https://dcoldeira.github.io/posts/2026-09-16-llm-verified-execution/)
  Keep the model to reasoning and let deterministic code own every number that reaches a user.

More at [dcoldeira.github.io](https://dcoldeira.github.io).

---

## Research

**QRL — Quantum Relational Language** · [entangledcode/qrl](https://github.com/entangledcode/qrl)
A relations-first quantum programming language where causal structure is a
type-level primitive: a program that type-checks as `Switch(d)` is provably
causally nonseparable. Full compiler pipeline to MBQC measurement patterns with
four backends (Perceval, PennyLane, graphix, Qiskit). Hardware-verified on
Quandela's photonic QPU (S = 2.61 ± 0.08). ~13,600 lines · 896 tests · 31 modules ·
[Zenodo preprint](https://doi.org/10.5281/zenodo.18292199) ·
[QRL Book](https://github.com/dcoldeira/qrl-book)

---

## Contact

[david@entangledcode.dev](mailto:david@entangledcode.dev) ·
[entangledcode.dev](https://entangledcode.dev) ·
[linkedin.com/in/dcoldeira](https://www.linkedin.com/in/dcoldeira)
