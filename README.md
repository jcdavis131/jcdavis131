# Cam Davis — Principal MLOps Engineer | Self-Evolving LLM Factory

![MLOps](https://img.shields.io/badge/MLOps-Self--Evolving%20Factory-blue)
![Python](https://img.shields.io/badge/Python-3.11%20%2B%20uv-black)
![Factory](https://img.shields.io/badge/Factory-Dottie%20LLM%20→%20Agent%20→%20Deploy-green)
![Live](https://img.shields.io/badge/Live-arxiviq.com-orange)

**I build closed-loop MLOps factories that train their own LLMs to power their own agent ecosystems.**

> Solo personal project, no connection to employer, built with public/free-tier only (R2/Workers/Supabase/HF ZeroGPU, ONNX WASM).

## 🚀 Flagship: Dottie — Self-Evolving LLM Factory + Agent OS

**[jcdavis131/dottie](https://github.com/jcdavis131/dottie)** — Train your own LLM to power harness+skills+deploy flywheel. One tool manifest: `scout`.

- **Flywheel:** Data Foundry 9.5M toks → Curator x6 → PACKED P0-P5 → WSD YaRN J-Space S1 hl8/S2 hl300/C hl30/P hl150 → Eval Gate → Serve → Agent → Skills → Build → Deploy arxiviq.com → Traces RL
- **Single CLI Doctrine:** LLM tool list = `[scout]`. Self-evolution via `scout forge new/from-openapi/from-mcp → cat → edit → test → skill install → retry`
- **Forge Engine:** `apps/scout-cli/bigbang/plugins/forge/cli.py` — shipped 4528f85, verified demo_tool cycle
- **MLOps Hygiene:** telemetry gitignored, CI checks telemetry-clean, uv workspace, Makefile, MIT
- **Live Console:** [arxiviq.com](https://arxiviq.com) [Architecture Map](https://agent.meta.ai/s/dottie-architecture-map)

```bash
scout --json --help
scout --json forge list
scout --json ava status
scout --json forge new github --domains api.github.com --network
```

---

## 🏀 Vector Suite — MTNN Embeddings

- **[vector-hoops](https://github.com/jcdavis131/vector-hoops)** — NBA chimera search | 12,966 seasons, MTNN v5 CQS 85.87% leakfree 0.977 recall@10 | [Live](https://hoops.dumbmodel.com)
- **[vector-equities](https://github.com/jcdavis131/vector-equities)** — SEC live 2741 FYs 283 tickers transformer | CQS 0.635
- **[vector-gridiron](https://github.com/jcdavis131/vector-gridiron)** — Fantasy cockpit MTNN MAE 4.268
- **[vector-pitch](https://github.com/jcdavis131/vector-pitch)** — World Cup chimera

All: era-z, tower families, offline-first CI, free-tier static deploy.

---

## 🐾 Scout CLI — Agent Control Plane

**[scout-cli](https://github.com/jcdavis131/scout-cli)** — 20+ plugins, capability-declared manifests, self-evolution.

- `scout ava` — factory, frontier eval 11 cats
- `scout forge` — self-evolution engine
- `scout rtx` — Alienware RTX 4080/4090 hill-climb offload
- `scout graphify` — code knowledge graph

---

## 📊 MLOps Principles I Ship

| Principle | Evidence |
|---|---|
| Reproducibility | uv workspace, Docker, pyproject, Makefile, DOTTIE_ROOT, train.sh |
| Data Versioning | Streaming manifests, curator x6, P0-P5 packs, 13-gram decontam, ledger.json |
| Training | WSD YaRN J-Space losses (reportability+broadcast 20%+selectivity+MI+router KL), nano/mini/base1b presets |
| Eval Gate | ava-open-harness J-Space + frontier rubric 11 cats + anti-mock test_no_mock.py + safety scanner F1 0.939 |
| Serving | FastAPI hot-reload, QK-Norm, streaming, tool calling |
| Agent OS | Hermes/OpenClaw demand queue, policy guardrails, flywheel |
| Self-Evolution | Single CLI doctrine, forge from-openapi/from-mcp, skill install teaches next session |
| Observability | telemetry.jsonl gitignored → arxiviq Control Plane, live_status, cron logs, hill-climb dashboard |
| Clean Hygiene | No telemetry tracked, CI telemetry-clean check, LICENSE MIT, badges |

---

## 📈 GitHub Stats

- 16 public repos, monorepo dottie canonical (subtree-merged 6 repos, history preserved)
- Top pinned: dottie, scout-cli, vector-hoops, ava-open-harness, personal-graphify, vector-equities

## 🛠️ Stack

Python 3.11 • PyTorch • uv • FastAPI • Typer • Ollama qwen3:32b • R2/Workers/Supabase/Vercel • HF ZeroGPU • ONNX WASM • ExecuTorch • Three.js • Mermaid

## 📫 Contact

Personal: jcdavis131@gmail.com | Work: camd@meta.com (work isolated to 03_Meta_Work_ISOLATED) | Live: arxiviq.com | dumbmodel.com ecosystem

---

Solo personal project disclaimer: All repos are built with public/free-tier only, no connection to employer, HOME-only per AGENTS.md two-personality separation.
