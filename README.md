# Matthew Kissinger

**Software engineer building developer tools, AI systems, and interactive software.**

I work in Python and TypeScript, from agent infrastructure and backend services to browser interfaces, real-time graphics, and simulation. My professional work includes production AI systems for Electrify America and earlier work in financial verification and federal healthcare modernization.

**Open to engineering roles and contract projects.** [matt@instruktlabs.com](mailto:matt@instruktlabs.com)  /  [Explore MK OS](https://mkos.instruktlabs.com/)

## Selected work

### [Kiln](https://github.com/instruktlabs/kiln)

An **MIT-licensed, open-source procedural 3D engine for coding agents**, actively developed in the [public GitHub repository](https://github.com/instruktlabs/kiln). Available on npm as **[`@instruktlabs/kiln`](https://www.npmjs.com/package/@instruktlabs/kiln)** under **Instrukt Labs**. [Explore KilnStudio.tools](https://kilnstudio.tools/).

Your agent writes JavaScript; Kiln runs it, returns rendered views and structural checks, and preserves the source for revision. Export a GLB and keep an editable asset rather than just its final mesh.

I built the engine, MCP server, CLI, TypeScript SDK, saved-revision workflow, and workspace tooling. Local plugins support Claude Code and Codex, with setup for other supported coding agents. [Installation](https://github.com/instruktlabs/kiln/blob/main/docs/install.md) · [Gallery](https://kilnstudio.tools/gallery/) · [Interactive scenes](https://kilnstudio.tools/scenes/)

A hosted beta relaunch is in progress, with general availability planned soon. I am working toward inclusion in the official Claude Code and Codex plugin libraries.

### [Sheepdog Sim](https://github.com/matthew-kissinger/sds)

A single-player browser game about guiding 25, 75 or 200 sheep into their pen. V3 includes keyboard, gamepad and touch controls, dog and flock customization, local records, online solo times, and personal run history. Built with TypeScript, React and Three.js, with WebGPU and WebGL2 rendering. **AGPL-3.0-or-later.** [Play Sheepdog Sim](https://sheepdogsim.com/).

In the 30 days ending October 7, 2026, Sheepdog Sim saw 7,652 new player profiles. V3 players completed 861 online runs, spending 78.3 hours herding 45,900 sheep. Those totals do not include unfinished or offline runs, so they capture only part of the activity. [Measurement details](https://mkos.instruktlabs.com/work/studies/sheepdog.html) explain profile identities and the reporting window. Multiplayer is planned.

### [AgentCore](https://github.com/matthew-kissinger/agentcore-skills) and [Strands](https://github.com/matthew-kissinger/strands-agents-skills) skills

Installable skills for coding agents, drawn from building, debugging, and retiring hosted Kiln:

- [AgentCore Skills](https://github.com/matthew-kissinger/agentcore-skills): TypeScript runtimes, streaming and sessions, Gateway identity and signing, and deployment operations.
- [Strands Agents Skills](https://github.com/matthew-kissinger/strands-agents-skills): provider integrations, tool loops, media handling, budgets, and consistent tool contracts across SDK, MCP, and CLI.

**MIT-licensed community projects**, with source-linked explanations and offline examples. They turn lessons from a working system into reusable guidance other engineers and their agents can inspect and apply.

### [MK OS](https://mkos.instruktlabs.com/)

My interactive portfolio is also a browser application I built: a TypeScript desktop with its own window manager, app runtime, virtual filesystem, and graphics and audio tools.

**Zero third-party runtime dependencies in the core desktop and simulation stack.** I built the window manager, filesystem, graphics, audio, and simulations in TypeScript, directly on the DOM, WebGPU/WebGL2, Web Audio, and worker APIs. No UI framework or runtime game engine.

The optional Kowalski local-model worker loads Transformers.js and ONNX Runtime on demand; those inference libraries are separate from the core stack.

Explore the engineering through these MK OS applications:

- [Ocean](https://mkos.instruktlabs.com/#/ocean): water and craft simulation.
- [Fallline](https://mkos.instruktlabs.com/#/fallline): freestyle skiing with carved turns and aerial control.
- [Boids](https://mkos.instruktlabs.com/#/boids): GPU flocking with a CPU reference for validation.
- [Shaderlab](https://mkos.instruktlabs.com/#/shaderlab): compare CPU, WebGPU, and WebGL2 shader results.
- [Planet](https://mkos.instruktlabs.com/#/planet): an orbitable world with terrain, biomes, and climate.

Live application; source private.

### [Three.js Field Grass](https://github.com/matthew-kissinger/threejs-field-grass)

A reusable interactive grass system with deterministic placement, wind, and movement-responsive deformation. Plain Three.js API with an optional React Three Fiber adapter. **MIT-licensed source preview.** [Interactive examples](https://matthew-kissinger.github.io/threejs-field-grass/)

## In development

### [Terror in the Jungle V3](https://vietnam-war-sim.pages.dev/)

My closed-source browser combat game, with first-person squad command, sector battles, combined arms, and worker-based simulation. The current playable build requires WebGPU. Development and performance work continue.

### [OBJEKT-62](https://objekt62.com/)

My closed-source browser salvage game with single-player exploration and private co-op. Its multiplayer systems use server authority, prediction and reconciliation, persistence, and shared vehicle crews. It is playable and in active development.

## Work with me

I build agent integrations, automation, backend services, internal tools, and interactive web applications. Python and TypeScript are my main languages; I use React, AWS, and the Strands Agents SDK, alongside Three.js and WebGPU for graphics work.

Much of my professional code lives in company repositories. The projects above show how I approach systems, tools, and usable interfaces in my own work.

For a role or project, reach me at **[matt@instruktlabs.com](mailto:matt@instruktlabs.com)**.
