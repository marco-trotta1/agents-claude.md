# agents-claude.md

Public agent context files from prominent AI builders and agent-tool authors.

The collection contains 35 direct source snapshots and 1 clearly marked community-derived snapshot. Direct snapshots keep the source path and file name. Each source revision is recorded in [research/SOURCES.md](research/SOURCES.md).

## Layout

- `people/` contains files published in repositories owned or maintained by the named person.
- `derived/` contains community files based on another person's public work.
- `research/` contains source links, revisions, search notes, and negative findings.

## Frontier-lab people

| Person | Lab | Public source | Main agent surface |
| --- | --- | --- | --- |
| Ashwin Bhat | Anthropic | `ashwin-ant/claude-code-action` | Claude Code action architecture and workflow |
| Boris Cherny | Anthropic | `bcherny/openclaw` | `AGENTS.md` and `CLAUDE.md` |
| Dickson Tsai | Anthropic | `dicksontsai/docs` | Blog writing, testing, and PR rules |
| Dominik Kundel | OpenAI | `dkundel-openai/openai-agents-python` | Agents SDK contributor rules |
| Tomer Aberbach | Anthropic | `TomerAberbach/claude-config` | Personal Claude Code configuration |

## Other included people

| Person | Public source | Main agent surface |
| --- | --- | --- |
| Andrej Karpathy | `karpathy/autoresearch`, `karpathy/nanochat` | Research runbook and Claude skill |
| Steve Yegge | `steveyegge/gastown`, `steveyegge/beads` | Agent entry points and detailed instructions |
| Simon Willison | `simonw/llm` | `AGENTS.md` |
| Matt Pocock | `mattpocock/skills` | `CLAUDE.md` and linked skills |
| Affaan Hussein | `affaan-m/everything-claude-code` | `AGENTS.md` and `CLAUDE.md` |
| Peter Steinberger | `steipete/agent-scripts`, `steipete/deepsec`, `steipete/claude-code-mcp` | Global rules and project entry points |
| Harrison Chase | `hwchase17/harbor`, `hwchase17/stagehand` | Agent evaluation and browser-agent context |
| Swyx | `swyxio/skills` | Progress reporting rule |
| Addy Osmani | `addyosmani/agent-skills` | Repository rules and skill workflow |
| Jesse Vincent | `obra/superpowers` | Agent methodology and contributor gates |
| Mitchell Hashimoto | `ghostty-org/ghostty` | Build rules and AI usage policy |
| Georgi Gerganov | `ggml-org/llama.cpp` | LLM project contribution rules |
| Samuel Colvin | `pydantic/pydantic-ai` | AI framework engineering rules |

Alexandr Wang was inspected, but no public agent-rule file was found in the reviewed sources.

## Attribution

The copied files are verbatim public snapshots. They may contain project-specific commands, links, and policy. Read the source note before using a file in another repository.

The collection does not claim that a repository owner wrote every line in a project. It claims only that the file was published in the named person's public repository or was clearly labeled as community-derived.
