# Student Creation Form — Field Schema

This schema reflects the field labels supplied for the student creation form. Required status, accepted values, and business rules must be verified in the application.

| Order | Field label | Test focus |
|---:|---|---|
| 1 | FIRST NAME | Required indicator, length, whitespace, supported name characters |
| 2 | LAST NAME | Required indicator, length, whitespace, supported name characters |
| 3 | IEP DUE | Date format, impossible dates, date-order rule if defined |
| 4 | EVAL DUE | Date format, impossible dates, date-order rule if defined |
| 5 | SERV TIME | Accepted numeric format, range, persistence |
| 6 | SCHOOL | Accepted value, empty/long values, persistence |
| 7 | GRADE | Available values, boundary options, persistence |
| 8 | DOB | Date format, impossible/future dates, date-order rules if defined |
| 9 | ROOM NUMBER | Accepted format, empty/long values, persistence |
| 10 | TEACHER | Free-text or selection behavior, available values, persistence |
| 11 | CASE MANAGER | Free-text or selection behavior, available values, persistence |
| 12 | ELIGIBILITY | Available options, selection behavior, persistence |

## Fictional baseline data for test execution

Use only synthetic data and adapt fields that require choosing an existing option in the app.

| Field | Example value |
|---|---|
| FIRST NAME | Jordan |
| LAST NAME | QAExample |
| IEP DUE | 12/15/2026 |
| EVAL DUE | 11/20/2026 |
| SERV TIME | 30 |
| SCHOOL | QA Demo School |
| GRADE | Choose an available test value |
| DOB | 03/12/2016 |
| ROOM NUMBER | 104 |
| TEACHER | Choose or enter an authorized test value |
| CASE MANAGER | Choose or enter an authorized test value |
| ELIGIBILITY | Choose an available test option |

Do not treat the example date order as an established product rule. Do not use real student names or records.
