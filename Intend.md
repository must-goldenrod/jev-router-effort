# JEV Router: evidence-driven improvement owner

Date: 2026-09-30. Owner: `jev-router-improver`. Source: the maintainer's Publisher incident review and six-part implementation request in this session.

## User intent

Keep inexpensive, fast responses for ordinary work while preventing routing and execution failures like the Publisher incident. A dedicated agent owns feedback intake, evidence analysis, criteria, implementation, verification and traceable improvements. A model recommendation's confidence is not a measured task-success probability.

## The five problems to solve

1. **Task-specific capability:** a generic tier name does not demonstrate ability. Gemini Pro mapped to `opus` does not establish equivalence to Claude Opus. Record exact CLI, model version, effort and observed task type. Use sufficiently supported task-specific evidence; retain existing tier routing for missing or insufficient evidence.
2. **Requirements before price:** identify ambiguity, cross-module scope, state transitions, persistent/background work and external effects. Select eligible models before optimizing cost and response time. Complexity metrics must influence policy rather than merely appear in a status display. Do not equate prompt length or one keyword with difficulty.
3. **Task context and failure feedback:** preserve the first objective, constraints, stage and user/QA failure reports across follow-ups. A short continuation must not erase the original task. Failure reports create inspectable cases and improvement issues; a model's completion claim is not a verified success.
4. **Cross-CLI execution:** when local candidates are unsuitable and sufficient evidence supports another CLI/model/effort, delegate through Orca to a real Claude or Codex executor. Carry objective, constraints, checkpoint, affected files and verification evidence. One writer owns a task at a time. Record acceptance, actual start and completion separately; never claim success from a send receipt.
5. **Execution safeguard:** destructive recovery must not erase pre-existing work. The maintainer chose a **Git checkpoint commit before complex work**, not automatic worktree creation. Preserve pre-existing tracked, staged and untracked work, fail before execution if a required checkpoint cannot be made, and do not automatically roll back a shared workspace. A checkpoint is recovery protection, not proof that every destructive shell command is intercepted.

## Incident evidence and limits

The locally identified Publisher case (source reference retained in `Analyzer/private/`) contains the original prompt, an initial `gemini-pro-agent` routing notice (confidence 0.57), and execution of `git reset --hard HEAD && git clean -fd` with exit 0 and deletion output. Do not infer the exact Gemini release from the alias. Do not apply today's candidate list retrospectively: the earlier adapter also recognized Claude. This is one failure, not a universal model ranking.

## Evidence and improvement lifecycle

- Analyze the most recent 24 hours first, reviewing at least 20% of eligible sessions across Claude, Codex and Antigravity. Expand to 48 hours only when coverage or task/model evidence is insufficient; 48 hours is the final requested maximum.
- `Analyzer/` owns the reproducible collection, sampling and analysis tools. Raw sessions, identifiers and private evidence stay local and Git-ignored. Record the denominator, sample, missing sources and unknown outcomes.
- `docs/` owns documented criteria plus a versioned machine-readable policy. Unknown model versions/efforts remain unknown; do not invent precise performance numbers.
- `issue/YYYY-MM-DD-*/` owns each change's `intend.md`, `directive.md`, results and regression evidence. Commit each finished issue separately. Preserve earlier decisions for regression tracking.
- Root `CLAUDE.md` and `AGENTS.md` make this contract discoverable. Global improvement and Claude/Codex executor agents use the same maintained harness.
- No history is required to install/use the router. Empty or insufficient evidence preserves the existing model/effort choice. The execution checkpoint is independently enabled by the user's safeguard configuration.

## Completion

Deliver discoverable agents, an executable analysis/feedback loop, an actual recent-session analysis, evidence-backed policy with honest abstention, task-aware runtime integration, tested checkpoint and Orca handoff paths, and per-issue commits. Report measured coverage, what was activated, unmeasured quality and any blocked deployment. No publishing, remote pushes or scheduled jobs are requested.
