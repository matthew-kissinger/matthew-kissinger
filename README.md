# Matthew Kissinger

**I build games, AI systems, and the tooling to make them.**

Developer working across real-time 3D (WebGL and WebGPU, Three.js/TSL), AI pipelines, and whatever the problem actually needs. I hand-roll the systems that matter - flocking, terrain, wave physics, multiplayer netcode - and when the tool I need doesn't exist, I build it.

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
| **wavy** · closed source | WebGPU ocean sandbox on Three.js TSL. A CPU/GPU twin: the same Gerstner wave math drives the GPU water surface and CPU-side buoyancy for drivable boats, with compute-shader foam and wake and dual above/below-water rendering. The lab behind the ocean work mentioned below. [Live build](https://matthew-kissinger.github.io/wavy/) |

## The arc

GPT-3 experiments (2023) → local model pipelines and vanilla-JS games (2024) → WebGPU engines, shipped multiplayer games, and production AI systems (2025-26).

The early public repos are still up: hand-rolled RAG with raw embeddings, [radar](https://github.com/matthew-kissinger/radar) (proto tool-calling and context recursion before that was standard tooling), [2DGAG](https://github.com/matthew-kissinger/2DGAG) (a local Stable Diffusion asset pipeline), [zoo-mcp](https://github.com/matthew-kissinger/zoo-mcp), plus a WebGPU ocean sim, a whale sim with sonar-as-vision, a PSX-style survival horror, and early experiments running coding-agent swarms unsupervised. Most of that stays private - old prototypes and stepping stones.

The heaviest AI work lives in the company repos of a previous role: a year of building enterprise AI pipelines - a dozen MCP servers (half deployed to Bedrock AgentCore), agent skills, case triage and resolution pipelines, classifiers, bug-hunting agents - plus a full-stack dev portal and a support portal, shipped solo. [kilnstudio.tools](https://kilnstudio.tools) exists partly to show that same stack and scale in public, built solo.

Before all of this I worked as a senior blockchain systems analyst. I intend to come back around to crypto eventually - there are systems I designed back then that the tooling couldn't build yet.

If there is one through-line, it's simulation. Boid flocking from CPU prototypes to 100k+ agents in WebGPU compute ([sds](https://github.com/matthew-kissinger/sds) → [sds-gpu-boids](https://github.com/matthew-kissinger/sds-gpu-boids)), cellular automata ([falling-sand-alchemy](https://github.com/matthew-kissinger/falling-sand-alchemy)), a streaming voxel planet on real polyhedron topology ([goldberg-planet](https://github.com/matthew-kissinger/goldberg-planet)), combat simulation for thousands of NPCs on real USGS terrain ([terror-in-the-jungle](https://github.com/matthew-kissinger/terror-in-the-jungle)), plus private work on Gerstner-wave oceans, whale kinematics with sonar-as-vision, and hand-rolled flight physics. Games are how I ship simulations people can touch.

Some repos here are deliberately frozen rather than maintained. Model generations move fast; a working orchestrator from six months ago is worth more as an artifact than as a codebase to drag forward.

Recurring habits: **CPU/GPU parity** (terrain math, wave math, and boid logic that run bit-identically on both), **hand-rolling core systems** instead of reaching for engines, and **shipping live URLs** - a project isn't done until someone can play it.
