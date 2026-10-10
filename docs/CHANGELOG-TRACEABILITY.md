# Changelog-to-Test Traceability

Source: [AbleSpace changelog](https://ablespace.canny.io/changelog), reviewed 10 October 2026.

| Changelog topic | Test case coverage |
|---|---|
| AI worksheet generation and editing | `worksheets/TC-WS-001` through `TC-WS-004` |
| Worksheet assignment, link/QR, response review and grading | `worksheets/TC-WS-005` through `TC-WS-007` |
| CPT code creation, permissions, deletion, use in session | `billing-cpt/TC-CPT-001` through `TC-CPT-004` |
| Existing progress notes by date range | `goals-reports/TC-GRP-001` |
| Independent and prompted accuracy | `goals-reports/TC-GRP-002` |
| Filter search | `filters/TC-FLT-001` |
| Bulk grade/age changes | `caseload-iep/TC-CAS-001` |
| IEP upload and review of extracted details | `caseload-iep/TC-IEP-001` |
| Service-type creation permission | `permissions/TC-PER-001` |
| Event lines on graphs | `graphs-data/TC-GRD-001`, `TC-GRD-002` |
| Custom fields in session data and AI progress notes | `sessions/TC-SES-001` |

The changelog provides workflow descriptions, not every validation rule. When requirements are unclear, record actual behavior and seek confirmation rather than asserting an assumed rule.