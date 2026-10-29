# INTTRA Documentation

A shared home for product requirements, operational specifications, EDI guidance, carrier integrations, compliance mandates, architecture decisions, and test documentation.

## Repository map

- [`templates/`](templates/): reusable BRD, done statement, EDI implementation guide, ADR, and release-note templates.
- [`docs/00-governance/`](docs/00-governance/): documentation standards, lifecycle, and style guide.
- [`docs/01-reference/`](docs/01-reference/): glossary, reference code-list sources, and channel comparison.
- [`docs/booking/`](docs/booking/): booking BRDs, optional validations, specifications, and release notes.
- [`docs/shipping-instructions/`](docs/shipping-instructions/): shipping-instruction requirements and behavior.
- [`docs/schedules/`](docs/schedules/): carrier schedule integrations.
- [`docs/visibility/`](docs/visibility/): shipment visibility requirements and specifications.
- [`docs/edi/`](docs/edi/): message guides, carrier implementation guides, and field mappings.
- [`docs/compliance/`](docs/compliance/): customs and regulatory mandates.
- [`docs/architecture/adr/`](docs/architecture/adr/): architecture decision records.
- [`docs/testing/`](docs/testing/): test plans and localization verification.
- [`assets/`](assets/): editable diagrams and exported images.

## Contributing

Start with [`CONTRIBUTING.md`](CONTRIBUTING.md) and the standards in [`docs/00-governance/`](docs/00-governance/). Use the relevant template, keep source diagrams editable, and submit changes through a pull request.

Markdown linting and link checks run on pull requests and pushes. The document-build workflow produces PDF and DOCX artifacts for Markdown files in `docs/` and `templates/`.
