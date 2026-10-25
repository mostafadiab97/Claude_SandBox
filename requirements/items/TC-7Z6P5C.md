---
id: TC-7Z6P5C
type: test-case
title: "Verify: Tamper detection displays access tokens"
status: Review
owner: Y. Saber
parent: INFO-Z4TW4B
order: 930
links:
  - type: verifies
    target: SYS-98RRJK
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
