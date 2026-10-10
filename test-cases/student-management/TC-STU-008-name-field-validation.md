# TC-STU-008 — First and last name validation

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** FIRST NAME, LAST NAME, IEP DUE, EVAL DUE, SERV TIME, SCHOOL, GRADE, DOB, ROOM NUMBER, TEACHER, CASE MANAGER, ELIGIBILITY (as relevant)
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
First and last name validation

## Preconditions
Open the student creation form.

## Test data
Use fictional and disposable data only. Refer to the field schema for labels and a synthetic baseline.

## Steps
For FIRST NAME and LAST NAME, try empty and whitespace-only values, leading/trailing spaces, long strings, digits, punctuation, a hyphenated name, and an apostrophe. Attempt to save and record outcomes.

## Expected result
Name handling follows defined field rules while allowing legitimate names. Typing acceptance alone is not enough to establish a defect; verify submit/save behavior.

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
Use fictional examples such as Alex123, Alex@#$, Anne-Marie, and O’Neil.
