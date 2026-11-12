# Marc Poliquin

I build software where AI meets the systems it runs on: a compiler stack for photonic hardware, a runtime that holds AI agents to hard limits, and an open reference on how modern AI works.

My background is corporate finance and accounting, and I am based in Miami. I build with AI coding agents. My part is the design, the acceptance criteria, the review, and the evidence that the result works: tests, CI gates, and written records of what was measured and what was only simulated.

## Projects

### [AWEN](https://github.com/marcpoliquin5/awen): compiler and runtime for photonic computing

Neural networks spend most of their time multiplying matrices, and programmable photonic circuits can do that with interfering light. AWEN takes a tensor program from PyTorch, JAX or StableHLO and decides what can run on a photonic matrix core, how to tile it, and how to check the result against a CPU reference.

- Rust compiler and runtime, MLIR dialects in C++, and a `torch.compile` backend in Python
- About 780 tests at the 0.1.0 release, with the commands and counts recorded in the repository
- Simulator-only so far: no photonic hardware has been used, and the README says so

Website: [awen-labs](https://github.com/marcpoliquin5/awen-labs) ([live](https://marcpoliquin5.github.io/awen-labs/)), a React and TypeScript site built around one persistent WebGL scene.

### [FINITE](https://github.com/marcpoliquin5/finite-agent-physics): a runtime that holds agent workflows to their limits

Agent frameworks describe what may happen next. FINITE checks whether a workflow can meet its deadline, token and cost budgets, and rate limits before any model is called, refuses work that cannot, replans when conditions change, and turns risky writes into reviewable, crash-safe intents.

- Python runtime with a CLI, an authenticated HTTP API, a 23-tool MCP server, and a Next.js console
- 1,020 tests, with coverage floors enforced in CI
- Experimental release candidate, not production software

### [Understanding AI](https://github.com/marcpoliquin5/understanding-ai): a sourced map of the field

A growing reference that runs from linear algebra and backpropagation to LLM serving, alignment, and photonic computing. It has more than 65 topic pages and 1,300 references, and each page explains the idea in plain language before the mathematics.

### Smaller projects

- [handbook-answerer](https://github.com/marcpoliquin5/handbook-answerer): answers HR policy questions from a live public handbook with a local model. Every answer cites its source passages, and the tool abstains when it cannot. One Python file, standard library only.
- [affordable-housing-finance](https://github.com/marcpoliquin5/affordable-housing-finance): breaks down the published financing for two Miami-Dade affordable housing developments by stage, and re-checks every figure against its source page.

## How the projects are kept accurate

Each repository states what is measured, what is simulated, and what is not done yet. Results come with the commands that produced them, and reference material cites its sources.
