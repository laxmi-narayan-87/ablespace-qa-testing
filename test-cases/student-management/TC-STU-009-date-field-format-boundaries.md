# TC-STU-009 — Date field format and boundaries

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** FIRST NAME, LAST NAME, IEP DUE, EVAL DUE, SERV TIME, SCHOOL, GRADE, DOB, ROOM NUMBER, TEACHER, CASE MANAGER, ELIGIBILITY (as relevant)
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
Date field format and boundaries

## Preconditions
Open student creation and use synthetic values for all non-date fields.

## Test data
Use fictional and disposable data only. Refer to the field schema for labels and a synthetic baseline.

## Steps
For IEP DUE, EVAL DUE, and DOB, try a valid date, a different format, an impossible date (02/30/2026), a leap date (02/29/2028), and a future date. Record validation and persistence for each.

## Expected result
Date fields accept valid dates in the supported format, reject impossible dates, and enforce documented future-date restrictions with accurate feedback.

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
TC-STU-001 and TC-STU-003 cover date relationships; TC-STU-005 focuses on error-message wording.
