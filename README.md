# Trimkeep plugin marketplace

A Claude Code plugin marketplace for [Trimkeep](https://trimkeep.com) guardrail tooling.

```
/plugin marketplace add trimkeep/claude-plugins
/plugin install handrail@trimkeep
```

## Plugins

- **handrail** — fail-closed deny/ask hooks for Claude Code: destructive shell, git
  force-push/reset, secret paths, prod-environment commands, package publish, remote code
  piped to a shell. Only tightens, never grants. MIT. Source and docs:
  https://github.com/trimkeep/handrail-kit · https://trimkeep.com/handrail-kit/

Handrail works with Claude Code and other agent CLIs in plain text only; it is not
affiliated with, endorsed by, or a product of Anthropic. Handrail is a defence-in-depth
layer — it reduces risk but does not eliminate it, is not a security audit or
certification, and does not replace backups, code review, or your own judgment.
