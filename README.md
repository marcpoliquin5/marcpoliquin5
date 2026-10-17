<div align="center">

## Computing with light · Agents that keep their promises · A living map of AI

</div>

I build software at the boundary between AI and the physical systems that run it: compilers for photonic hardware, runtimes that hold AI agents to explicit limits, and an open, sourced knowledge base on how AI works and where it is going.

Every project here follows the same rule: **say only what the evidence supports.** Capabilities are documented with their limits, and speculation is labelled as speculation.

---

### AWEN: photonic computing platform

Neural networks spend most of their time multiplying matrices, and light can do that by interference. AWEN is the software stack for programmable photonic linear algebra.

| Repository | What it is |
|---|---|
| [**awen**](https://github.com/marcpoliquin5/awen) | Experimental compiler and runtime: tensor-to-photonic compilation, MLIR dialects for StableHLO matrix multiplication, calibration-aware tiling and fault remapping, a seeded analog-noise simulator, and a PyTorch `torch.compile` backend. Rust · MLIR · Python |
| [**awen-labs**](https://github.com/marcpoliquin5/awen-labs) | Interactive platform website. React · TypeScript · Vite |
| [**awenphotonics.github.io**](https://github.com/marcpoliquin5/awenphotonics.github.io) | Static status site with an evidence policy that blocks unsupported claims ([visit](https://marcpoliquin5.github.io/awenphotonics.github.io/)) |

### FINITE: agent physics

> *Agents can reason. FINITE makes them keep promises.*

[**finite-agent-physics**](https://github.com/marcpoliquin5/finite-agent-physics) is an experimental, framework-neutral runtime for AI agent workflows. It compiles deadlines, token and cost ceilings, provider capacity, and side effects into typed contracts, refuses impossible work before dispatch, and turns consequential writes into durable, reviewable intents. Python · TypeScript

### Understanding AI

[**understanding-ai**](https://github.com/marcpoliquin5/understanding-ai) is a living, sourced map of artificial intelligence, updated daily. It runs from foundations (linear algebra, probability, optimization) through deep learning, LLMs, systems and alignment to the frontiers: recursion and self-improvement, fractal scaling, nonlinear dynamics, photonic and neuromorphic computing, quantum ML, and world models. Every claim links to a checked reference.

### Other projects

| Repository | What it is |
|---|---|
| [**handbook-answerer**](https://github.com/marcpoliquin5/handbook-answerer) | Retrieval-augmented answers from a live public handbook using a local model, with citations and explicit abstention |
| [**affordable-housing-finance**](https://github.com/marcpoliquin5/affordable-housing-finance) | Sourced review of published affordable-housing financing that keeps construction and permanent financing stages separate, with live source verification |
