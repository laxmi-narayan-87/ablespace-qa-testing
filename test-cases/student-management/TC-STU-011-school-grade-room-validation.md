# TC-STU-011 — SCHOOL, GRADE, and ROOM NUMBER validation

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** FIRST NAME, LAST NAME, IEP DUE, EVAL DUE, SERV TIME, SCHOOL, GRADE, DOB, ROOM NUMBER, TEACHER, CASE MANAGER, ELIGIBILITY (as relevant)
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
SCHOOL, GRADE, and ROOM NUMBER validation

## Preconditions
Open student creation.

## Test data
Use fictional and disposable data only. Refer to the field schema for labels and a synthetic baseline.

## Steps
Inspect whether SCHOOL and GRADE are selectors or free text. Try a valid available value, blank value, and long input where permitted. For ROOM NUMBER, try a typical value, alphabetic/alphanumeric value, whitespace, and a long value. Save and reopen where possible.

## Expected result
Each field accepts documented values and clearly validates any required/range restrictions; saved values are consistent with input.

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
Do not assume ROOM NUMBER must be numeric or SCHOOL is free text.
