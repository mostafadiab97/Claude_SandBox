---
id: TC-Z71QV0
type: test-case
title: "Verify: Tamper detection notifys audit records"
status: Obsolete
priority: Medium
owner: M. Farouk
parent: INFO-Z4TW4B
order: 650
links:
  - type: verifies
    target: SYS-8ZC1RT
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
