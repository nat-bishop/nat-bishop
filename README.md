# Hi, I'm Nat

I'm a product engineer building AI agent systems, procedural 3D tools and GPU simulation.

## Projects

### [Halation](https://github.com/nat-bishop/halation)

**Procedural 3D that stays editable.** Describe an asset or scene, work with an agent on its typed node graph, and keep the recipe for further edits and variations. Halation combines a desktop authoring workflow, OpenUSD and Cycles rendering, and validation tools for articulated assets used in robotics simulation.

[![A volcanic massif rendered in Halation](https://raw.githubusercontent.com/nat-bishop/halation/master/docs/hero.png)](https://github.com/nat-bishop/halation)

Python · Rust · TypeScript · Pydantic AI · OpenUSD · Cycles · Electron

[Explore the project and architecture →](https://github.com/nat-bishop/halation)

*Public case study; implementation private.*

### [Halation Fluid](https://github.com/nat-bishop/halation-fluid)

**GPU liquid, smoke and fire simulation in Rust and wgpu.** I built the engine from simulation kernels through resumable caches and a Houdini integration, with numerical benchmarks and blind visual comparisons guiding development.

[![Liquid responding to a moving container](https://raw.githubusercontent.com/nat-bishop/halation-fluid/main/media/development/container-motion.gif)](https://github.com/nat-bishop/halation-fluid)

Rust · wgpu / WGSL · FLIP / APIC · Houdini · OpenVDB

[See the simulations and engineering case study →](https://github.com/nat-bishop/halation-fluid)

*Public case study; implementation private.*

### More projects

- **[Cosmos Houdini Pipeline](https://github.com/nat-bishop/cosmos-houdini-pipeline):** orchestrates NVIDIA Cosmos video generation on remote H100 GPUs for synthetic training data.
- **[Finance Agent](https://github.com/nat-bishop/finance-agent):** a research copilot that writes and executes analytical queries against prediction-market data.
- **[Financial Planner](https://github.com/nat-bishop/financial-planner):** bank syncing, a real-time 2FA relay and LLM transaction categorization.

<details>
<summary>Earlier experiments</summary>

- **[Tutorial Agent](https://github.com/nat-bishop/tutorial-agent):** turns video tutorials into interactive lessons validated in Photoshop and Blender.
- **[Browser Recorder](https://github.com/nat-bishop/browser-recorder):** turns recorded browser sessions into reusable automations.
- **[Job Search Agent](https://github.com/nat-bishop/job-search-agent):** searches for jobs, extracts career pages and persists structured results.
- **[Image Classifier](https://github.com/nat-bishop/image-classifier):** extracts and scores color palettes, with a Nuke VFX plugin.

</details>

## Open-source contributions

Selected code changes merged upstream:

- **[Blender / Cycles](https://projects.blender.org/blender/blender/pulls/163988):** preserved the coarse vertex count during repeated subdivision tessellation in Hydra.
- **[Cycles](https://projects.blender.org/blender/cycles/pulls/80):** fixed a buffer overrun when importing vector primvars through Hydra.
- **[Cycles](https://projects.blender.org/blender/cycles/pulls/69):** fixed volume rendering so scaling an object preserves its optical depth.
- **[Pydantic AI](https://github.com/pydantic/pydantic-ai/pull/4649):** added support for Google's 512 image-generation size in validation, types and documentation.

[LinkedIn](https://www.linkedin.com/in/nat-bishop/) · [ArtStation](https://nat_bishop.artstation.com/)
