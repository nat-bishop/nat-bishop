# Hi, I'm Nat

I'm an AI and product engineer. I build deterministic guardrails around stochastic models so they can be trusted where being wrong is expensive. At work I build agent infrastructure and evals. On my own time I build AI agent systems, procedural 3D tools and GPU simulation.

## Projects

### [Halation](https://github.com/nat-bishop/halation)

**An AI agent edits a procedural 3D document, and deterministic checks decide whether its work is right.** The agent writes a typed recipe that a person can open and change, not a one-off mesh. Halation outputs OpenUSD and renders in Cycles; articulated assets for robotics simulation are certified in Isaac Sim, and the agent is measured by a 198-case eval suite.

[![A procedural countertop microwave in Halation, its door swinging open](https://raw.githubusercontent.com/nat-bishop/halation/master/docs/media/halation-hero.gif)](https://github.com/nat-bishop/halation)

*A procedural microwave authored in Halation's recipe language and rendered in Cycles. The repo's video shows the agent building one, failing certification and repairing it.*

Python · Rust · TypeScript · Pydantic AI · OpenUSD · Cycles · Isaac Sim · Electron

[See the agent catch and repair a physics failure →](https://github.com/nat-bishop/halation)

*Public case study; implementation private.*

### [Halation Fluid](https://github.com/nat-bishop/halation-fluid)

**GPU liquid, smoke and fire simulation in Rust and wgpu.** I built the engine from simulation kernels through resumable caches and a Houdini integration, with numerical benchmarks and blind visual comparisons guiding development.

[![Smoke wrapping a sphere, a torch flame and water pouring into a glass, simulated side by side in Halation Fluid](https://raw.githubusercontent.com/nat-bishop/halation-fluid/main/media/halation-fluid-hero.gif)](https://github.com/nat-bishop/halation-fluid)

*Smoke, fire and FLIP/APIC liquid, simulated side by side on the GPU and rendered in Cycles.*

Rust · wgpu / WGSL · FLIP / APIC · Houdini · OpenVDB

[See the simulations and engineering case study →](https://github.com/nat-bishop/halation-fluid)

*Public case study; implementation private.*

### More projects

- **[Pant Goch](https://github.com/nat-bishop/pant-goch):** an LLM-driven folk-noir investigation game. The model writes prose and a grammar-constrained engine writes state, so the model cannot invent a story beat or location it has no permission for.
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

- **[Blender / Cycles](https://projects.blender.org/blender/blender/pulls/163988):** fixed Cycles subdivision so tessellating an already-diced mesh again keeps its original coarse vertex count.
- **[Cycles](https://projects.blender.org/blender/cycles/pulls/80):** fixed a buffer overrun when importing vector primvars through Hydra.
- **[Cycles](https://projects.blender.org/blender/cycles/pulls/69):** fixed Hydra volume import so uniformly scaling a volume or changing stage units keeps its optical depth.
- **[Pydantic AI](https://github.com/pydantic/pydantic-ai/pull/4649):** added support for Google's 512 image-generation size in validation, types and documentation.

[LinkedIn](https://www.linkedin.com/in/nat-bishop/) · [ArtStation](https://nat_bishop.artstation.com/)
