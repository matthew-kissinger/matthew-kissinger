# Matthew Kissinger

**I build browser games and the AI tooling to make them.**

Solo developer working across real-time 3D (WebGL and WebGPU, Three.js/TSL) and AI asset pipelines. I hand-roll the systems that matter - flocking, terrain, wave physics, multiplayer netcode - and when the tool I need doesn't exist, I build it.

<!-- capture slots: 2-up gameplay grid goes here (sds + titj), see SHOTLIST.md -->

## Playing now

**[sheepdogsim.com](https://sheepdogsim.com)** · [source](https://github.com/matthew-kissinger/sds)
Browser-based 3D sheep herding game. Solo leaderboard modes, 2-4 player online co-op and competitive rooms, split-screen, a sandbox editor, full mobile + gamepad support. Three.js with WebGL fallback and progressive WebGPU, React 19, Cloudflare Workers + Durable Objects. Fully open source (AGPL-3.0) - a complete shipped multiplayer game you can read end-to-end.

**[terror-in-the-jungle.pages.dev](https://terror-in-the-jungle.pages.dev)** · [source](https://github.com/matthew-kissinger/terror-in-the-jungle)
Combined-arms Vietnam-theater FPS/RTS sandbox // infantry, ground vehicles, helicopters, and fixed-wing aircraft in one runtime, architected for ~3,000 NPCs on real A Shau Valley DEM terrain. WebGPU/TSL, 314k lines, 5,900+ tests.

**[objekt62.com](https://objekt62.com)** · closed source
Multiplayer salvage-horror in the browser. Authoritative-server netcode on Cloudflare Durable Objects with client-side prediction and reconciliation, deterministic CPU/GPU terrain parity. The code is private IP - the game is live.

## Building

**[kilnstudio.tools](https://kilnstudio.tools)** · closed source
Text-to-3D GLB generation with a pairwise model-ranking arena, deployed on AWS - Bedrock AgentCore Runtime, ECS Fargate, DynamoDB, Cognito, CDK-managed infra. The current endpoint of three years of AI asset-pipeline work.

## R&D

| | |
|---|---|
| [**sds-gpu-boids**](https://github.com/matthew-kissinger/sds-gpu-boids) | WebGPU compute-shader flocking sandbox. 100k+ agents, prefix-scan spatial grid, CPU reference oracle validating the GPU pipeline. The lab behind Sheep Dog Simulator. [Live experimental build](https://matthew-kissinger.github.io/sds-gpu-boids/) |
| [**goldberg-planet**](https://github.com/matthew-kissinger/goldberg-planet) | Demo concept: a walkable, flyable, mineable planet whose surface is a true Goldberg polyhedron, topology derived from scratch. [Live demo](https://matthew-kissinger.github.io/goldberg-planet/) |
| [**mycelium-v2**](https://github.com/matthew-kissinger/mycelium-v2) | Multi-agent orchestration for CLI coding agents. Deliberately archived - a frozen snapshot of what agent orchestration looked like in early 2026, kept as reference for the next rebuild. |
| [**falling-sand-alchemy**](https://github.com/matthew-kissinger/falling-sand-alchemy) | Zen falling-sand game about transmutation. Pure cellular automaton in TypeScript drawn through a WebGL2 bloom pipeline. [Play it](https://matthew-kissinger.github.io/falling-sand-alchemy/) |

## The arc

GPT-3 experiments (2023) → local model pipelines and vanilla-JS games (2024) → WebGPU engines, shipped multiplayer games, and deployed AI SaaS (2025-26).

Along the way: hand-rolled RAG before LangChain existed, research agents, Stable Diffusion asset pipelines, local inference UIs, MCP servers in the earliest days of the protocol ([zoo-mcp](https://github.com/matthew-kissinger/zoo-mcp), [radar](https://github.com/matthew-kissinger/radar), [2DGAG](https://github.com/matthew-kissinger/2DGAG) are still up), a WebGPU ocean sim, a whale sim with sonar-as-vision, a PSX-style survival horror, and an agent swarm that shipped ten small games unsupervised. Most of that work stays private - old prototypes, space junk, and ideas that earned their keep as stepping stones. The lineage that mattered became kilnstudio.tools and the games above.

Some repos here are deliberately frozen rather than maintained. Model generations move fast; a working orchestrator from six months ago is worth more as an artifact than as a codebase to drag forward.

Recurring habits: **CPU/GPU parity** (terrain math, wave math, and boid logic that run bit-identically on both), **hand-rolling core systems** instead of reaching for engines, and **shipping live URLs** - a project isn't done until someone can play it.
