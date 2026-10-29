# EDI and Web channel matrix

Use this matrix as a starting point for documenting channel-specific behavior. Confirm each value for the product and workflow being specified; do not assume feature parity.

| Concern | EDI channel | Web channel | Document per workflow |
|---|---|---|---|
| Submission | Partner-generated message using an agreed standard/profile | User-entered or uploaded information | Supported formats, required fields, limits |
| Validation | Syntax, partner profile, and business rules | UI validation and business rules | Rules, timing, and error presentation |
| Acknowledgement | Message-level and application-level response as configured | In-product status or notification | Events, latency, and retry behavior |
| Error correction | Correct and resubmit according to partner guidance | Edit and resubmit where supported | Ownership, audit trail, and resubmission constraints |
| Availability | Integration and partner connectivity dependent | Application access and permissions dependent | Service window, fallback, and support path |

For a concrete process, link its BRD, specification, EDI guide, and test plan, and call out any intentional differences between channels.
