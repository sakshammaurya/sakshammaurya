# GitHub Portfolio Tracker

Last updated: 2026-10-26

## Task tracker

| ID | Priority | Repository | Task | Status | Evidence / notes |
|---|---|---|---|---|---|
| SPEECH-001 | P1 | [briskk-speech-assignment](https://github.com/sakshammaurya/briskk-speech-assignment) | Correct README's outdated statement that no automated test suite exists | DONE | Updated README to retain the accurate limitation that deployment configuration is not included. [Commit](https://github.com/sakshammaurya/briskk-speech-assignment/commit/9d6976694f6e274c635f059ee81066df9de0374c). Documentation-only change; tests not run. |
| AUTH-001 | P1 | [login-signup](https://github.com/sakshammaurya/login-signup) | Inspect and fix SQL injection in login query; add a focused regression test | TODO | Root cause and affected call paths still need repository inspection. |
| AUTH-002 | P1 | [login-signup](https://github.com/sakshammaurya/login-signup) | Review verification-token generation, storage, expiry, and validation | TODO | Inspect implementation before deciding on a minimal security fix and tests. |
| ECOM-001 | P2 | [ecommerce-website](https://github.com/sakshammaurya/ecommerce-website) | Identify one important uncovered behavior and add focused automated tests | TODO | Inspect current test setup and choose one high-value failure path. |
| RAG-001 | P2 | New repository / TBD | Create a minimal production-style RAG service skeleton with tests | TODO | Proposed stack: Python, FastAPI, PostgreSQL/pgvector, pytest; implement in independently verifiable milestones. |
| WEBHOOK-001 | P3 | New repository / TBD | Build a webhook-processing service demonstrating idempotency, retries, and failure recovery | TODO | Start with one small, tested milestone after higher-priority existing repositories. |
| PROFILE-001 | P3 | [profile repository](https://github.com/sakshammaurya/sakshammaurya) | Keep profile README aligned with verified project evidence and resume | TODO | Review claims and links periodically; avoid unsupported metrics. |

## Daily work log

### 2026-10-26
- **Completed:** SPEECH-001 — removed an outdated README limitation that contradicted the documented pytest suite and GitHub Actions workflow.
- **Changed file:** `README.md` in `sakshammaurya/briskk-speech-assignment`.
- **Verification:** Confirmed the old sentence existed before editing and the GitHub Contents API accepted the update. No tests were run because this was a documentation-only change. CI status was not checked.
- **Commit:** [9d6976694f6e274c635f059ee81066df9de0374c](https://github.com/sakshammaurya/briskk-speech-assignment/commit/9d6976694f6e274c635f059ee81066df9de0374c)
- **Next action:** AUTH-001 — inspect the login query in `login-signup`, fix one confirmed SQL injection path, and add a targeted regression test.

## Working rules
- Mark tasks DONE only when supported by evidence.
- Keep one implementation task per work session.
- Record actual verification; never imply tests or CI passed unless checked.
- Add newly discovered issues as follow-ups rather than expanding the current task.
