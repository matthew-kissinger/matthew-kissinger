# Matthew Kissinger

**I build browser games — and the AI tooling to make them.**

Solo developer working across real-time 3D graphics (WebGL & WebGPU, Three.js/TSL) and AI asset pipelines. I hand-roll the systems that matter — flocking, terrain, wave physics, multiplayer netcode — and when the tool I need doesn't exist, I build it.

---

## 🎮 Playing now

**[sheepdogsim.com](https://sheepdogsim.com)** · [source →](https://github.com/matthew-kissinger/sds)
A browser-based 3D sheep herding game: solo leaderboards, 2–4 player online co-op, split-screen, sandbox editor, full mobile + gamepad support. Three.js with WebGL fallback and progressive WebGPU, React 19, Cloudflare Workers + Durable Objects. Fully open source (AGPL-3.0) — a complete shipped multiplayer game you can read end-to-end.

**[terror-in-the-jungle.pages.dev](https://terror-in-the-jungle.pages.dev)** · [source →](https://github.com/matthew-kissinger/terror-in-the-jungle)
Combined-arms Vietnam-theater FPS/RTS sandbox — infantry, ground vehicles, helicopters, and fixed-wing aircraft in one runtime, architected for ~3,000 NPCs on real A Shau Valley DEM terrain. WebGPU/TSL, 314k lines, 5,900+ tests.

**[objekt62.com](https://objekt62.com)** · closed source
Multiplayer salvage-horror in the browser. Authoritative-server netcode on Cloudflare Durable Objects with client-side prediction and reconciliation, and deterministic CPU/GPU terrain parity. The code is private IP — the game is live.

## 🔨 Building

**[kilnstudio.tools](https://kilnstudio.tools)** · closed source
Text-to-3D GLB generation with a pairwise model-ranking arena, deployed on AWS — Bedrock AgentCore Runtime, ECS Fargate, DynamoDB, Cognito, CDK-managed infrastructure. The endpoint of a three-year lineage of AI asset-pipeline work.

## 🧪 R&D

| | |
|---|---|
| [**sds-gpu-boids**](https://github.com/matthew-kissinger/sds-gpu-boids) | WebGPU compute-shader flocking sandbox — 100k+ agents, prefix-scan spatial grid, CPU reference oracle validating the GPU pipeline. The lab behind Sheep Dog Simulator. |
| [**goldberg-planet**](https://github.com/matthew-kissinger/goldberg-planet) | Survival sandbox on a Goldberg polyhedron sphere — topology derived from scratch. [Live demo](https://matthew-kissinger.github.io/goldberg-planet/) |
| [**mycelium-v2**](https://github.com/matthew-kissinger/mycelium-v2) | Orchestrating fleets of AI coding agents — Claude Code, Codex, Gemini — as a production development methodology. |
| [**falling-sand-alchemy**](https://github.com/matthew-kissinger/falling-sand-alchemy) | Zen falling-sand alchemy game on WebGL2 — cellular automata with a crafting system. |

## The arcs

GPT-3 Flask wrappers (2023) → local model pipelines and vanilla-JS games (2024) → WebGPU engines, shipped multiplayer games, and deployed AI SaaS (2025–26). Every repo on this profile is a step in one of four lines:

<details>
<summary><b>🕹️ Vanilla JS game dev → WebGPU engine author</b></summary>
<br>

| | | |
|---|---|---|
| 2023 | [Space-Hive-Battle](https://github.com/matthew-kissinger/Space-Hive-Battle) | Pygame prototype, single file |
| 2024 | [TimeDrift](https://github.com/matthew-kissinger/TimeDrift.github.io) · [vector-hazard-zone](https://github.com/matthew-kissinger/vector-hazard-zone) | Vanilla JS Canvas 2D arcade games |
| 2024 | [terror-in-the-jungle-vr-experimental](https://github.com/matthew-kissinger/terror-in-the-jungle-vr-experimental) | Three.js + WebXR, GPU-instanced vegetation |
| 2025 | [goldberg-planet](https://github.com/matthew-kissinger/goldberg-planet) · [Asteroid-Miner](https://github.com/matthew-kissinger/Asteroid-Miner) · [the-nightman-cometh](https://github.com/matthew-kissinger/the-nightman-cometh) · [sperm-whale-sim](https://github.com/matthew-kissinger/sperm-whale-sim) · wavy *(private)* | WebGPU-native games: TSL shaders, bitECS, Gerstner waves, PSX horror |
| 2026 | [terror-in-the-jungle](https://github.com/matthew-kissinger/terror-in-the-jungle) · [sds](https://github.com/matthew-kissinger/sds) · [objekt62.com](https://objekt62.com) *(closed source)* | Shipped multiplayer games — real DEM terrain, authoritative netcode, 314k LOC |

</details>

<details>
<summary><b>🤖 GPT-3 experimenter → production AI builder</b></summary>
<br>

| | | |
|---|---|---|
| 2023 | [CourseAI-V2](https://github.com/matthew-kissinger/CourseAI-V2) · [radar](https://github.com/matthew-kissinger/radar) | Hand-rolled RAG with ada-002 (pre-LangChain), iterative GPT-4 research agent |
| 2023 | [2DGAG](https://github.com/matthew-kissinger/2DGAG) | Local Llama + Stable Diffusion game-asset pipeline |
| 2024 | [llama-prime](https://github.com/matthew-kissinger/llama-prime) · [b0tf4rm](https://github.com/matthew-kissinger/b0tf4rm) | Local inference UIs, fleets of LLM Discord bots |
| 2025 | [hyperspace](https://github.com/matthew-kissinger/hyperspace) · [firehose-cli](https://github.com/matthew-kissinger/firehose-cli) · [zoo-mcp](https://github.com/matthew-kissinger/zoo-mcp) · [hyper-mcp](https://github.com/matthew-kissinger/hyper-mcp) | Reasoning shells, multi-model analysis, MCP servers |
| 2025–26 | kiln → [kilnstudio.tools](https://kilnstudio.tools) *(closed source)* | Production text-to-3D SaaS on AWS Bedrock AgentCore |

</details>

<details>
<summary><b>🕸️ Manual developer → AI-agent fleet operator</b></summary>
<br>

| | | |
|---|---|---|
| 2025 | [agent-orchestrator-mcp-server](https://github.com/matthew-kissinger/agent-orchestrator-mcp-server) | MCP server orchestrating Claude Code, Codex, Gemini, Cursor |
| 2026 | [mycelium](https://github.com/matthew-kissinger/mycelium) → [mycelium-v2](https://github.com/matthew-kissinger/mycelium-v2) | Autonomous agent loop with evaluator + human-in-the-loop → 10-agent orchestrator with a React Flow control surface |
| 2026 | [sbox-workspace](https://github.com/matthew-kissinger/sbox-workspace) · [sheep-dog-sim](https://github.com/matthew-kissinger/sheep-dog-sim) | An unsupervised agent swarm shipped 10 s&box games; a full C# game port built agent-first |

</details>

<details>
<summary><b>🎨 Asset generator → commercial text-to-3D product</b></summary>
<br>

The longest line in the portfolio: [2DGAG](https://github.com/matthew-kissinger/2DGAG) (2023, Stable Diffusion sprites) → pixforge → pixel-forge (LLM-as-programmer 3D generation) → kiln (private engine with a deterministic CPU rasterizer so the model can see its own output, plus a Bradley-Terry ranking arena) → [kilnstudio.tools](https://kilnstudio.tools) (2026, deployed SaaS). Each step exists because the previous approach hit a real limitation.

</details>

Some repos here are deliberately frozen — generational snapshots of what agent orchestration looked like on a given model generation ([mycelium-v2](https://github.com/matthew-kissinger/mycelium-v2) is archived at the Opus 4.6 / GPT-5.2 era), kept as reference for the next rebuild rather than maintained. Things move quickly; the artifacts are the point.

Recurring obsessions: **CPU/GPU parity** (terrain math, wave math, and boid logic that run bit-identically on both — four projects and counting), **hand-rolled core systems** over off-the-shelf engines, and **shipping live URLs** — a project isn't done until someone can play it.

<!--
TODO: add gameplay GIFs
- capture 10-15s of sheepdogsim.com gameplay -> assets/sds.gif (<10MB)
- capture 10-15s of objekt62.com gameplay -> assets/objekt62.gif
- capture terror-in-the-jungle helicopter run -> assets/titj.gif
- embed as a 2-column HTML table above "Playing now"
-->
