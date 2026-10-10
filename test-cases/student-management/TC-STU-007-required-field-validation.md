# TC-STU-007 — Required-field validation

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** FIRST NAME, LAST NAME, IEP DUE, EVAL DUE, SERV TIME, SCHOOL, GRADE, DOB, ROOM NUMBER, TEACHER, CASE MANAGER, ELIGIBILITY (as relevant)
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
Required-field validation

## Preconditions
Open student creation and note visible required markers such as an asterisk.

## Test data
Use fictional and disposable data only. Refer to the field schema for labels and a synthetic baseline.

## Steps
Attempt to save with the form empty; then remove one visibly required field at a time from a synthetic baseline record and retry. Record field-level messages and whether data saves.

## Expected result
The form enforces fields marked required and identifies missing values clearly. Do not assume all 12 fields are required unless the UI indicates that.

## Actual result
_Not tested — fill in after execution. Do not infer a result._

## Execution record
- Date/time:
- OS/device:
- Browser/version:
- Viewport/resolution:
- Status: Not tested
- Evidence:
- Notes:

## Notes / limitations
Record required indicators exactly as shown.
