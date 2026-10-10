# TC-STU-005 — Invalid date feedback

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** IEP DUE, EVAL DUE, DOB
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
Check whether feedback for impossible dates is specific and actionable.

## Preconditions
Open student creation and prepare fictional values for the other fields.

## Steps
1. Try an impossible date such as 02/30/2026 in IEP DUE.
2. Repeat with EVAL DUE and DOB if the form permits.
3. Attempt validation/save and capture the exact field-level message.
4. Check whether the message accurately identifies an impossible date, format issue, or range issue.

## Expected result
The message clearly explains the invalid input and identifies the affected field.

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
A generic format/future-date message was previously reported; capture exact wording before classifying as a usability defect.
