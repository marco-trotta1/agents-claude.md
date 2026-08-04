# Awesome AGENTS.md and CLAUDE.md

[![GitHub stars](https://img.shields.io/github/stars/marco-trotta1/awesome-agents-md?style=flat-square)](https://github.com/marco-trotta1/awesome-agents-md/stargazers)
[![Catalog license](https://img.shields.io/badge/catalog-CC%20BY%204.0-blue?style=flat-square)](LICENSE)

Source-linked examples of agent context files from official labs and leading AI builders.

Study real `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, and `SKILL.md` files. Compare how experienced teams define context, testing, verification, permissions, and agent workflows.

If this catalog helps you build a better agent workflow, [star it](https://github.com/marco-trotta1/awesome-agents-md).

Last audited: 2026-08-04.

## Start here

- [Boris Cherny](people/boris-cherny/) for a concise Anthropic-linked project entry point.
- [Andrej Karpathy](people/andrej-karpathy/) for research iteration and Claude skill guidance.
- [OpenAI Codex](labs/openai/codex/AGENTS.md) for a large production agent repository.
- [Anthropic Skill Creator](labs/anthropic/skills/skill-creator/SKILL.md) for structured agent instructions.
- [Google Gemini CLI](labs/google/gemini-cli/GEMINI.md) for a first-party Gemini context file.

## At a glance

| Collection | Direct files | Purpose |
| --- | ---: | --- |
| [Official labs](labs/) | 5 | Files published by OpenAI, Anthropic, and Google repositories. |
| [People](people/) | 36 | Files published by or associated with named people. |
| [Derived](derived/) | 1 | A clearly marked community file based on public work. |

## Official lab sources

| Lab | Repository | Included files | Main focus |
| --- | --- | --- | --- |
| OpenAI | [codex](labs/openai/codex/) | [`AGENTS.md`](labs/openai/codex/AGENTS.md) | Rust architecture, tests, sandboxing, and review rules |
| OpenAI | [openai-agents-python](labs/openai/openai-agents-python/) | [`AGENTS.md`](labs/openai/openai-agents-python/AGENTS.md) | SDK structure, skills, testing, and contributor workflow |
| Anthropic | [skills](labs/anthropic/skills/) | [`README.md`](labs/anthropic/skills/README.md), [`skill-creator/SKILL.md`](labs/anthropic/skills/skill-creator/SKILL.md) | Official skill format and skill evaluation workflow |
| Google | [gemini-cli](labs/google/gemini-cli/) | [`GEMINI.md`](labs/google/gemini-cli/GEMINI.md) | Gemini CLI architecture, development, and testing |

The official lab label describes repository ownership. It does not imply endorsement of this catalog.

## People

| Person | Lab or role | Source | Main agent surface |
| --- | --- | --- | --- |
| Ashwin Bhat | Anthropic | [claude-code-action](people/ashwin-bhat/) | Claude Code action architecture and workflow |
| Boris Cherny | Anthropic | [openclaw](people/boris-cherny/) | `AGENTS.md` and `CLAUDE.md` |
| Dickson Tsai | Anthropic | [docs](people/dickson-tsai/) | Blog writing, testing, and PR rules |
| Dominik Kundel | OpenAI | [openai-agents-python](people/dominik-kundel/) | Agents SDK contributor rules |
| Tomer Aberbach | Anthropic | [claude-config](people/tomer-aberbach/) | Personal Claude Code configuration |
| Andrej Karpathy | Independent AI researcher | [autoresearch and nanochat](people/andrej-karpathy/) | Research runbook and Claude skill |
| Steve Yegge | Agent-tool builder | [gastown and beads](people/steve-yegge/) | Agent entry points and detailed instructions |
| Simon Willison | AI tool builder | [llm](people/simon-willison/) | `AGENTS.md` |
| Matt Pocock | TypeScript educator | [skills](people/matt-pocock/) | `CLAUDE.md` and linked skills |
| Marcos Hernandez | Public X source | [X post](people/marcos-hernandez/) | `AGENTS.md` |
| Affaan Hussein | Agent-tool builder | [everything-claude-code](people/affaan-hussein/) | `AGENTS.md` and `CLAUDE.md` |
| Peter Steinberger | Agent-tool builder | [agent-scripts, deepsec, and claude-code-mcp](people/peter-steinberger/) | Global rules and project entry points |
| Harrison Chase | Agent-tool builder | [harbor and stagehand](people/harrison-chase/) | Agent evaluation and browser-agent context |
| Swyx | Developer educator | [skills](people/swyx/) | Progress reporting rule |
| Addy Osmani | Former Google Gemini and Cloud director | [agent-skills](people/addy-osmani/) | Repository rules and skill workflow |
| Jesse Vincent | Software developer | [superpowers](people/jesse-vincent/) | Agent methodology and contributor gates |
| Mitchell Hashimoto | Ghostty creator | [ghostty](people/mitchell-hashimoto/) | Build rules and AI usage policy |
| Georgi Gerganov | LLM tool builder | [llama.cpp](people/georgi-gerganov/) | LLM project contribution rules |
| Samuel Colvin | Pydantic founder | [pydantic-ai](people/samuel-colvin/) | AI framework engineering rules |

## How to use this catalog

1. Choose a source from the lab or people index.
2. Read the local attribution note before reusing a file.
3. Open the source ledger to inspect its URL, branch, and revision.
4. Copy only rules that fit your project and that you can verify.

These files are examples. They are not universal policies or drop-in instructions for every repository.

## Selection and attribution

- Direct snapshots are copied from public source repositories.
- Derived snapshots are marked and linked to their public basis.
- Source revisions are recorded in [research/SOURCES.md](research/SOURCES.md).
- Source snapshots keep the license and terms of their original repositories.
- A person's inclusion does not imply that they wrote every line in a project.

Alexandr Wang was reviewed, but no public agent context file was found in the sources checked.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the source requirements and update process.

## Research notes

The [source ledger](research/SOURCES.md) records GitHub, X, Hacker News, Devpost, and profile research. It also records negative findings so that future updates do not repeat the same checks.
