# Documentation status lifecycle

Use one of these statuses in controlled documents:

| Status | Meaning |
|---|---|
| Draft | Work in progress; not authoritative for implementation. |
| In Review | Submitted for review; changes may still be requested. |
| Approved | Reviewed by accountable stakeholders and authoritative for its stated scope. |
| Deprecated | Superseded or no longer applicable; retain for history and link to the replacement when available. |

## Transitions

- **Draft → In Review:** the owner considers the content complete enough for stakeholder review.
- **In Review → Draft:** reviewers request substantive changes.
- **In Review → Approved:** required reviewers approve and the owner records the approval date.
- **Approved → In Review:** a material change is proposed; retain the existing approved version until the new version is approved.
- **Approved → Deprecated:** the content is retired or replaced; identify the replacement or reason where possible.

Status does not replace pull-request review or release approval. A document's scope and effective date must be clear when they differ from the repository's current state.
