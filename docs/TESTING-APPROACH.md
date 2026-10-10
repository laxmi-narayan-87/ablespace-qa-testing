# Testing Approach

## Purpose
Evaluate key user workflows, form validation, navigation, reporting, AI-assisted worksheet creation, and responsive usability in AbleSpace.

## Method
- Manual exploratory testing and functional validation.
- Negative and boundary input checks where rules are known.
- Use product changelog entries to identify workflows and observable behaviors.
- Maintain one test case per file so results and evidence can be tracked independently.

## Status definitions
- **Not tested:** no execution recorded.
- **Pending verification:** tester-reported observation exists but needs reproduction or business-rule confirmation.
- **Pass / Fail / Blocked:** use only after running the case and recording actual behavior.
- **Candidate defect:** not yet sufficiently reproduced or expected behavior not confirmed.

## Data and scope constraints
Use one authorized test account and fictional data only. Avoid repeated scripted account creation. Do not test security/penetration/load behavior. Review evidence for private or identifying information before committing.