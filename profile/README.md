# pragmatic-engineer

Playbook is a Claude Code plugin and CLI for disciplined AI-assisted engineering. It ships skills, slash commands, subagents and safety and state hooks for planning, review, memory and guarded editing, and a `playbook` binary that runs the hooks.

Start with the [quick start](https://github.com/pragmatic-engineer/playbook#quick-start-1-command) and the [docs](https://github.com/pragmatic-engineer/playbook/blob/main/docs/index.md).

| Repo | What it is | Install |
|---|---|---|
| [playbook](https://github.com/pragmatic-engineer/playbook) | The plugin, the `playbook` binary and the docs. | `curl -fsSL https://raw.githubusercontent.com/pragmatic-engineer/playbook/main/install.sh \| bash` |
| [playbook-telemetry](https://github.com/pragmatic-engineer/playbook-telemetry) | Usage and cost dashboard for Claude Code sessions, alias `pbtop`. | `playbook usage` with playbook, or download a binary from the [releases](https://github.com/pragmatic-engineer/playbook-telemetry/releases/latest) |
| [playbook-code](https://github.com/pragmatic-engineer/playbook-code) | Code index and search, alias `pbcode`. Placeholder, not released yet. | None yet |
| [playbook-data](https://github.com/pragmatic-engineer/playbook-data) | Shared storage library, not a command. Placeholder, not released yet. | None, it is a library |
| [homebrew-tap](https://github.com/pragmatic-engineer/homebrew-tap) | Homebrew formula for the `playbook` binary. | `brew install pragmatic-engineer/tap/playbook` |
| [marketplace](https://github.com/pragmatic-engineer/marketplace) | Claude Code plugin marketplace that lists playbook. | `claude plugin marketplace add pragmatic-engineer/marketplace` then `claude plugin install playbook@pragmatic-engineer` |

Community files for all repos live in [.github](https://github.com/pragmatic-engineer/.github): [contributing](https://github.com/pragmatic-engineer/.github/blob/main/CONTRIBUTING.md), [security](https://github.com/pragmatic-engineer/.github/blob/main/SECURITY.md) and [support](https://github.com/pragmatic-engineer/.github/blob/main/SUPPORT.md).
