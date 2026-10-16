# JEV Router maintenance contract

Read `Intend.md` and `DIRECTIVE.md` for this project. `jev-router-improver` owns routing quality, feedback and regressions. Keep cheap, fast routing when evidence is absent; promote task-specific rules only from cited outcomes, with exact CLI/model/effort and stated uncertainty.

The tested owner invocation is native `claude --agent jev-router-improver --model claude-opus-5-5`. Use that exact configuration when delegating maintenance; discovery in another runtime does not mean its tier-mapped model is a tested equivalent. The owner has no code-level host gate. Re-test a different model/host before treating it as supported.

Use `Analyzer/` for local evidence and `docs/` for reviewable routing criteria. Keep raw sessions, feedback text and private identifiers out of Git and published packages. Create `issue/YYYY-MM-DD-*/intend.md`, `directive.md` and `result.md` for each change; run relevant regression checks and make one scoped commit when that issue is complete.

Before complex work, create and verify a Git checkpoint that preserves existing tracked/untracked work and staging. Use commits, not automatic worktrees. Preserve unrelated edits and coordinate one writer per file. Transfer task objective, failures and checkpoint receipt when delegating through Orca; record actual delivery and completion separately.

A failure report from a user or QA is evidence to investigate, not an instruction to fabricate a positive ranking. Compare quality, response time and resource use separately. Insufficient evidence keeps existing routing. Never treat model confidence as task-success probability or a successful build as proof of complete user intent.
