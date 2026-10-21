# pragmatic-engineer

Playbook is a Claude Code plugin and CLI for disciplined AI-assisted engineering. It ships skills, slash commands, subagents and safety and state hooks for planning, review, memory and guarded editing, and a `playbook` binary that runs the hooks.

Start with the [playbook README](https://github.com/pragmatic-engineer/playbook#readme) and the [docs](https://github.com/pragmatic-engineer/playbook/blob/main/docs/README.md).

| Repo | What it is | Install |
|---|---|---|
| [playbook](https://github.com/pragmatic-engineer/playbook) | The plugin, the `playbook` binary, the `pbtop` usage and cost dashboard and the docs. | `brew install pragmatic-engineer/tap/playbook`, then `playbook setup`. Or run the [install script](https://github.com/pragmatic-engineer/playbook/blob/main/install.sh): `curl -fsSL https://raw.githubusercontent.com/pragmatic-engineer/playbook/main/install.sh \| bash` |
| [homebrew-tap](https://github.com/pragmatic-engineer/homebrew-tap) | Homebrew formulas for `playbook` and `pbtop`. | `brew install pragmatic-engineer/tap/playbook` |
| [marketplace](https://github.com/pragmatic-engineer/marketplace) | Claude Code plugin marketplace that lists playbook. | `claude plugin marketplace add pragmatic-engineer/marketplace` then `claude plugin install playbook@pragmatic-engineer` |
| [.project-template](https://github.com/pragmatic-engineer/.project-template) | Template for new Rust library crates. | Use it as a GitHub template. |
| [playbook-telemetry](https://github.com/pragmatic-engineer/playbook-telemetry) | Archived. Replaced by `pbtop` and `playbook usage`. | Not needed. |

Homebrew 6.0.0 and later asks you to trust non-official taps. The fully qualified install above trusts only that formula. To use short names or trust the whole tap, see the [tap install notes](https://github.com/pragmatic-engineer/homebrew-tap#trust-the-tap).

Community files for all repos live in [.github](https://github.com/pragmatic-engineer/.github): [contributing](https://github.com/pragmatic-engineer/.github/blob/main/CONTRIBUTING.md), [security](https://github.com/pragmatic-engineer/.github/blob/main/SECURITY.md) and [support](https://github.com/pragmatic-engineer/.github/blob/main/SUPPORT.md).
