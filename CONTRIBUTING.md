# Contributing

## Branches and pull requests

- Create a focused branch from `main`, using `docs/<area>-<short-description>` (for example, `docs/booking-amendment-rules`).
- Keep a pull request focused on one feature, message, mandate, or decision where practical.
- Use the repository pull request template. Explain the behavior or requirement being documented, identify affected audiences and systems, and link related issues or decisions.
- Request review from the relevant subject-matter experts and resolve review comments before merging.
- Do not publish credentials, customer data, or other sensitive information. Use synthetic examples.

## Files and naming

- Use Markdown (`.md`) for authored documentation and UTF-8 text.
- Use lowercase, hyphen-separated slugs for general filenames (for example, `booking-amendment.md`).
- Name booking BRDs `BRD-BKG-0001-<slug>.md`, replacing the identifier and slug as appropriate.
- Give numbered records stable, unique identifiers. Do not reuse retired identifiers.
- Keep diagrams in editable `.drawio` or `.mmd` form under `assets/`; commit exported `.png` or `.svg` only when useful to readers.

## Review flow

1. Select the applicable template and check existing documentation for overlap.
2. Draft the change with status, owner, and review date where the template calls for them.
3. Validate links, terminology, examples, and any EDI field or code-list references.
4. Open a pull request with the scope, impact, and verification details.
5. After approval, merge using the repository's configured merge policy. Update status and related release notes when the change becomes effective.

See [`docs/00-governance/documentation-standards.md`](docs/00-governance/documentation-standards.md) and [`docs/00-governance/status-lifecycle.md`](docs/00-governance/status-lifecycle.md) for the documentation rules.
