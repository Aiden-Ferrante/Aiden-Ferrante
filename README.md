# Aiden Ferrante

Data science MS student at UConn. I build LLM agent systems on local hardware, then audit how they fail.
Most of what's here is a record of finding my own mistakes: silent failures behind green exit codes,
results that didn't survive a holdout, and three published self-retractions.

## Projects

| Project | What it shows |
| --- | --- |
| [fleetmcp](https://github.com/Aiden-Ferrante/fleetmcp) | 50 approval-gated MCP tools for agents; a lethal-trifecta audit of every tool (37 private data, 37 untrusted content, 0 egress); 12/12 eval runs including refusal cases |
| [crossfolio](https://github.com/Aiden-Ferrante/crossfolio) | A pre-registered neural portfolio allocator that didn't beat a simple baseline, reported as a negative result |
| [feedwall](https://github.com/Aiden-Ferrante/feedwall) | 24,178 items scored by a local LLM, and an audit of three silent failures |
| [manalab](https://github.com/Aiden-Ferrante/manalab) | A simulation study where an audit found 746 wrong values past a 391-test green suite, followed by three retractions |
| [learnhub-core](https://github.com/Aiden-Ferrante/learnhub-core) | Local LLM pipelines that turn textbook PDFs into a concept layer and practice items; 175 tests |
| [shipyard-pbtr](https://github.com/Aiden-Ferrante/shipyard-pbtr) | A planning tool that refuses at the API: no unmeasured goals, no review with uncommitted work, no destructive write without a token |

## Elsewhere

- Blog: [aiden-ferrante.github.io](https://aiden-ferrante.github.io)
- YouTube: [Ferrante²](https://www.youtube.com/@ferrante_2x), ML explainers
