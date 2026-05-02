# AgentKit Hooks Pack

Production-ready Claude Code Hook templates for teams.

**Status:** Pre-launch. Public release end of May 2026 under Apache 2.0.

## What ships at launch

Six templates covering the full Claude Code hook lifecycle:

- **PreToolUse permission gating** — the four-state state machine pattern
- **PostToolUse audit log** — JSON Lines with PII redaction
- **Kill switch sentinel** — file-based emergency stop
- **Notification routing** — macOS / Slack / webhook fan-out
- **Permission rewrite pattern** — translate dangerous commands before allow
- **Stop hook cleanup** — session-end /tmp lockfile cleanup

Plus seven docs (lifecycle events, permission model, failure modes, CI/CD integration, compliance audit log, rollout checklist) and three drop-in `settings.json` templates (solo / small-team / enterprise).

## License

Apache 2.0. All templates are free to use, modify, and ship in your team's setup.

## What we are publishing in the meantime

- 2026-05-02 — [PreToolUse Hooks Are a Tiny State Machine: The Four Exit Codes That Actually Matter](https://dev.to/agentkit/pretooluse-hooks-are-a-tiny-state-machine-the-four-exit-codes-that-actually-matter-2bg3) (live, dev.to)
- 2026-05-07 — *PostToolUse Hooks for Audit Logs: A Production Pattern with Code* (next)

Watch this repo or follow [@imta71770](https://x.com/imta71770) on X for the launch.

## Built by

[AgentKit](https://agentkit.gumroad.com) — production system audits for AI engineering teams.
