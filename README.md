# David Coldeira

**A quantum language, an assistant that runs it live, and the agent that builds both.**

Bristol, UK · EU citizen · ten years in software · physics graduate · Linux (Debian) user

I design, build and run production systems from scratch: architecture, backend,
frontend, deployment. When a language model goes into one of them, deterministic
code checks its output before it reaches a user or a database, and permissions
are enforced by the system rather than by the prompt.

---

## The connected work

**[QRL](https://github.com/entangledcode/qrl)** — a relations-first quantum
programming language where causal structure is a type-level primitive: a
program that type-checks as `Switch(d)` is provably causally nonseparable, a
result no existing quantum programming language can state. Full compiler
pipeline to MBQC measurement patterns across four backends (Perceval,
PennyLane, graphix, Qiskit). Hardware-verified on Quandela's photonic QPU
(S = 2.61 ± 0.08). ~13,600 lines · 896 tests · 31 modules ·
[Zenodo preprint](https://doi.org/10.5281/zenodo.18292199) ·
[QRL Book](https://github.com/dcoldeira/qrl-book)

**[Bell](https://bell.entangledcode.dev)** — the fine-tuned assistant that runs
QRL live. Plain English in, real QRL code executed, real numbers out — not the
model guessing a number. Provider-swappable: running on Mistral (EU-hosted)
today, a self-hosted Qwen3-8B fine-tune (815 training pairs) in standby.
Sandboxed execution, Podman/Caddy on Hetzner. **Try it.**

**[Froe](https://github.com/dcoldeira/froe)** — the local-first coding agent
used to build both. A single static Go binary for the terminal and Neovim.
Source never has to leave the machine. MIT licensed, public.

---

## Production AI engineering

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

---

## Writing

- [Putting an LLM on a Production Database, Read-Only by Construction](https://dcoldeira.github.io/posts/2026-09-16-llm-production-database/)
  Four independent layers, only one of which actually matters, and why the prompt is the layer you should trust least.
- [Don't Let the Model Do the Physics](https://dcoldeira.github.io/posts/2026-09-16-llm-verified-execution/)
  Keep the model to reasoning and let deterministic code own every number that reaches a user.

More at [dcoldeira.github.io](https://dcoldeira.github.io).

---

## Contact

[david@entangledcode.dev](mailto:david@entangledcode.dev) ·
[entangledcode.dev](https://entangledcode.dev) ·
[linkedin.com/in/dcoldeira](https://www.linkedin.com/in/dcoldeira)
