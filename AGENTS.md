# n8Mouse+ Agent Contract

This repository contains cross-machine input and clipboard software. Review the README, existing source/tests and any upstream provenance before editing.

- Preserve explicit device pairing, platform permissions, and privacy/security boundaries for keyboard, mouse, clipboard, and file transfer.
- Never create hidden input capture, persistence, or unapproved remote-control capability. Avoid leaking tokens, pairing codes, clipboard contents, or host addresses in logs.
- Preserve Windows/macOS platform distinctions and release packaging contracts. Do not claim a target works without tests on that target.
- Never install software, alter local system permissions, or release binaries as a side effect of routine source edits.

<!-- BEGIN SHARED AGENT SELF-AUDIT v1 -->
## Mandatory pre-completion adversarial self-audit

Before claiming completion or requesting review, inspect the full task-scoped change against an explicit review base: committed branch diff, staged and unstaged changes, and relevant untracked files. Record base/HEAD and preserve unrelated user changes. A bare `git diff` is not the whole candidate.

Look for concrete correctness and edge-case defects, concurrency/races, fail-closed behavior, API/schema compatibility, security and authority boundaries, durability, resource leaks/cleanup, missing positive and negative tests, and unnecessary complexity or out-of-scope edits. Tie each finding to a location and credible failure scenario; do not invent stylistic defects or churn working code.

Repair confirmed defects only within authorized scope, rerun affected checks, and reinspect remediation. Use at most two repair/re-review cycles by default; if blocked, report `INCOMPLETE` or `FAIL` instead of looping or weakening tests/invariants. Escalate changes requiring new authority.

Pre-existing failures are not waived by showing they also occur on the baseline. Separate cause attribution from resolution: repair the confirmed root cause when authorized, or create/link an owned, actionable remediation work item with reproduction, evidence, and a validation gate. Preserve failures and keep project-level health accurately red or incomplete until resolved. Never use permanent skips, false evidence, or weakened assertions to manufacture green results.

Handoff must state `Self-Audit: PASS|INCOMPLETE|FAIL`, reviewed revision and scope, concrete findings/fixes (or no confirmed findings), actual checks/results, unrun checks, and residual risks. PASS means review completed with no known in-scope blockers, not proof of defect freedom. Self-review is neither independent approval nor authorization to merge, deploy, release, publish, or perform destructive operations.
<!-- END SHARED AGENT SELF-AUDIT v1 -->
