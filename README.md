# Matthew Kissinger

**Software engineer building AI systems, developer tools, and interactive web applications.**

I work in Python and TypeScript, from agent infrastructure and backend services to browser interfaces, real-time graphics, and simulation. My professional work includes production AI systems for Electrify America and earlier work in financial verification and federal healthcare modernization.

**Open to engineering roles and contract projects.** [Email me](mailto:matt@instruktlabs.com) · [Explore MK OS](https://mkos.instruktlabs.com/)

## Selected work

### [Kiln](https://github.com/matthew-kissinger/kiln)

An open-source toolkit for building editable 3D assets with coding agents. The agent writes JavaScript; Kiln executes it, renders views, and returns structural checks for revision. Assets export as GLB while their source stays editable.

I built the engine and tooling: an MCP server, CLI, TypeScript library, and agent workflows. Kiln grew out of my hosted Kiln Studio product and now runs locally. **MIT licensed.** [Gallery and setup](https://kilnstudio.tools/)

### AgentCore and Strands skills

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

### [Sheepdog Sim](https://sheepdogsim.com/)

A shipped single-player browser game about guiding a flock into its pen. The current version includes keyboard, gamepad, and touch controls, dog and flock customization, local records, and optional online solo times. Built with React, TypeScript, and Three.js, with WebGPU and WebGL2 rendering. **[Source: AGPL-3.0](https://github.com/matthew-kissinger/sds).**

Recently rebuilt; multiplayer is planned to return in a future update.

### [Three.js Field Grass](https://github.com/matthew-kissinger/threejs-field-grass)

A reusable interactive grass system with deterministic placement, wind, and movement-responsive deformation. Plain Three.js API with an optional React Three Fiber adapter. **MIT-licensed source preview.** [Interactive examples](https://matthew-kissinger.github.io/threejs-field-grass/)

## In development

**Terror in the Jungle** is my browser-based Vietnam combat simulation. I am rebuilding it around first-person squad command and sector battles, with a separate asset workshop and worker-based simulation. [Current public playtest](https://vietnam-war-sim.pages.dev/) (work in progress; WebGPU required; source private) · [Original open-source project](https://github.com/matthew-kissinger/terror-in-the-jungle) · [Original playable build](https://terror-in-the-jungle.pages.dev/)

## Work with me

I build agent integrations, automation, backend services, internal tools, and interactive web applications. Python and TypeScript are my main languages; I use React, AWS, and the Strands Agents SDK, alongside Three.js and WebGPU for graphics work.

Much of my professional code lives in company repositories. The projects above show how I approach systems, tools, and usable interfaces in my own work.

For a role or project, reach me at **[matt@instruktlabs.com](mailto:matt@instruktlabs.com)**.
