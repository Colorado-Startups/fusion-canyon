# Security

## Report a vulnerability

Use [Report a vulnerability](https://github.com/Colorado-Startups/fusion-canyon/security/advisories/new), GitHub's private reporting, for anything in this repo. Please do not open a public issue. A person replies.

## How outside changes are kept safe

| Control | Where |
|---|---|
| Every fork run waits for approval and gets no secrets | Repo settings; `pull_request`, never `pull_request_target` |
| AI agents merge only content paths, at the reviewed head SHA, and never approve | [`CONTRIBUTING.md`](CONTRIBUTING.md) |
| CI, tool and instruction changes are rebuilt by the orchestrator, never merged as sent | [`CONTRIBUTING.md`](CONTRIBUTING.md) |
| Secret scanning and push protection on | Repo settings |
