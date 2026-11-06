# Aiden Ferrante

Data science MS student at UConn, with insurance data experience from an MGA. I build LLM pipelines and agent systems that pair models with deterministic checks and human approval, then measure how they fail.

**Stack:** Python · FastAPI · PostgreSQL · React / Next.js · Docker · pytest · GitHub Actions · LLM agents, MCP, evals

## Projects

| Project | What it shows |
| --- | --- |
| [learnhub-core](https://github.com/Aiden-Ferrante/learnhub-core) | Document pipeline: textbook PDF → table of contents → LLM concept extraction → an independent critic → a grounding check that traced 1,463 of 1,463 quotes back to the source. FastAPI, Postgres, Next.js; 212 tests in CI against Postgres |
| [fleetmcp](https://github.com/Aiden-Ferrante/fleetmcp) | One MCP server generated from four apps' OpenAPI specs: 50 tools, and destructive calls refused without a fresh impact token. `make demo` shows a refusal end to end; 12/12 agent eval runs, including refusal cases |
| [agentic-video-pipeline](https://github.com/Aiden-Ferrante/agentic-video-pipeline) | The build system behind my YouTube channel: one shot-list contract, adapters for ElevenLabs, ComfyUI and Stable Audio, a doit task graph, and MCP tools with a human in the loop |
| [shipyard-pbtr](https://github.com/Aiden-Ferrante/shipyard-pbtr) | A planning service that enforces its rules at the API: no unmeasured goals, no review with uncommitted work, no destructive write without a token. 437 tests |
| [manalab](https://github.com/Aiden-Ferrante/manalab) | A rules engine and simulator that reproduces Karsten's mana tables. An audit found 746 wrong values hiding behind a 391-test green suite; it now has 615 tests |
| [crossfolio](https://github.com/Aiden-Ferrante/crossfolio) | A pre-registered model with leakage probes, purged splits and a holdout wall. A free baseline won, and it's reported as a negative result. `crossfolio demo` recovers a planted signal on CPU in about a minute |
| [feedwall](https://github.com/Aiden-Ferrante/feedwall) | A local LLM scored 24,178 news items; an audit found three silent failures behind green exit codes, now made visible and tested |

Every project's tests run from a fresh clone in CI, and every README has a "What went wrong" section.

## Elsewhere

- YouTube: [Ferrante²](https://www.youtube.com/@ferrante_2x), ML explainers
- [LinkedIn](https://www.linkedin.com/in/aiden-ferrante-27a307271)
