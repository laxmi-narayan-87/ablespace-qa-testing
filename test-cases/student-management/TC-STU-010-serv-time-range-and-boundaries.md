# TC-STU-010 — SERV TIME range and numeric boundaries

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** FIRST NAME, LAST NAME, IEP DUE, EVAL DUE, SERV TIME, SCHOOL, GRADE, DOB, ROOM NUMBER, TEACHER, CASE MANAGER, ELIGIBILITY (as relevant)
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
SERV TIME range and numeric boundaries

## Preconditions
Open student creation with other required fields populated using synthetic values.

## Test data
Use fictional and disposable data only. Refer to the field schema for labels and a synthetic baseline.

## Steps
Test zero, positive integer 30, decimal 30.5, negative -1, a very large value, and blank input if permitted. Save or trigger validation and inspect persistence.

## Expected result
Values conform to documented units, precision, and allowed range. If no range is documented, record behavior rather than assuming a limit.

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
TC-STU-002 focuses on letters/mixed strings; this case focuses on numeric boundaries and precision.
