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

## The arc

GPT-3 Flask wrappers (2023) → local model pipelines and vanilla-JS games (2024) → WebGPU engines, shipped multiplayer games, and deployed AI SaaS (2025–26). Every repo on this profile is a step in that line.

Recurring obsessions: **CPU/GPU parity** (terrain math, wave math, and boid logic that run bit-identically on both — four projects and counting), **hand-rolled core systems** over off-the-shelf engines, and **shipping live URLs** — a project isn't done until someone can play it.

<!--
TODO: add gameplay GIFs
- capture 10-15s of sheepdogsim.com gameplay -> assets/sds.gif (<10MB)
- capture 10-15s of objekt62.com gameplay -> assets/objekt62.gif
- capture terror-in-the-jungle helicopter run -> assets/titj.gif
- embed as a 2-column HTML table above "Playing now"
-->
