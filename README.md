# AbleSpace QA Testing

Manual QA assessment repository for https://staging.ablespace.io.

- **Public product reference:** https://ablespace.canny.io/changelog
- **Status:** Test cases and structure prepared; execution status is recorded per case.
- **Test data:** Use fictional student/guardian information only.
- **Evidence:** Evidence folders are placeholders until genuine screenshots/recordings are added.

## Repository structure

- `docs/` — test approach, changelog traceability, and execution summary
- `test-cases/` — feature-based hierarchy with one Markdown file per test case
- `bug-reports/` — candidate bugs, kept separate and not treated as confirmed without reproduction
- `test-matrix/` — cross-browser and responsive matrix
- `evidence/` — empty folders for screenshots and recordings by environment
- `playwright/` — optional automation planning

## Test integrity

A changelog entry helps derive scenarios but does not prove current staging behavior. The test cases are drafts until executed. Only mark Pass/Fail after recording actual behavior and environment. Do not commit real student/guardian data, credentials, access tokens, or sensitive information.

No security, penetration, or load testing is in scope.