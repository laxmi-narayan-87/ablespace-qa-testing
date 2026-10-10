# TC-STU-001 — IEP Due and Eval Due date relationship

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** IEP DUE, EVAL DUE
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
Determine how the student creation form handles a relative ordering between IEP DUE and EVAL DUE.

## Preconditions
Open student creation and use fictional values for all 12 fields.

## Steps
1. Fill FIRST NAME, LAST NAME, SERV TIME, SCHOOL, GRADE, DOB, ROOM NUMBER, TEACHER, CASE MANAGER, and ELIGIBILITY with ordinary synthetic values.
2. Set IEP DUE to 10/20/2026 and EVAL DUE to 10/15/2026.
3. Save and record validation feedback.
4. If saved, reopen the record and verify both dates.

## Expected result
Follow an explicitly defined product rule for IEP/EVAL date ordering. If no rule is established, record observed behavior without asserting that this combination is invalid.

## Actual result
_Not tested — fill in after execution._

## Execution record
- Date/time:
- OS/device:
- Browser/version:
- Viewport:
- Status: Not tested
- Evidence:
- Notes:

## Notes / limitations
The tester previously reported this combination appeared to be accepted; save behavior and intended rules require confirmation.
