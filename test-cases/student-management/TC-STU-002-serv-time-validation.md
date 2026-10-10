# TC-STU-002 — Validate Serv Time input type

- **Status:** Not tested
- **Priority:** To be assessed after risk review
- **Fields:** SERV TIME
- **Related schema:** STUDENT-FIELD-SCHEMA.md

## Objective
Check whether SERV TIME accepts only formats supported by the product.

## Preconditions
Open student creation. Fill other required fields with fictional values as indicated by the UI.

## Steps
1. Enter SERV TIME = 30 and note whether it is accepted.
2. Replace it with 30abc and then abc.
3. Attempt to save each invalid-looking value where possible.
4. If a record saves, reopen it and inspect the stored SERV TIME value.

## Expected result
Only the documented SERV TIME format and range should be accepted. Do not assume whether units or suffixes are allowed until confirmed.

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
The tester reported mixed numeric/string input could be typed; typing alone does not prove it is saved or violates a product rule.
