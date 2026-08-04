# AI Server Operator

An open-source, self-hosted control plane that turns server alerts into explainable, approval-gated operations.

> Early development. The first public milestone connects existing monitoring data, diagnoses resource pressure, proposes a safe plan, asks for approval, executes through a restricted agent, and verifies the result.

## Community edition

- Self-hosted and free
- Linux server inventory and health summaries
- Human-readable incident diagnosis
- Approval required before every write action
- Command allowlists, timeouts, audit logs, and rollback metadata
- Bring your own model provider

## Product boundary

The public website and authenticated service share one brand and navigation, but run across separate security boundaries:

- `www`: marketing, docs, blog, pricing, and search content
- `app`: authenticated control plane
- `api`: versioned machine API
- `status`: public service health

See [docs/product-standard.md](docs/product-standard.md).

## Status

The current lab monitors four Linux servers through Beszel. The repository starts with the public product contract and safety model; the remediation agent is the next milestone.

## License

Apache-2.0. See [LICENSE](LICENSE).
