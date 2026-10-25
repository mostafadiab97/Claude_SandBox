---
id: TC-4AM1F6
type: test-case
title: "Verify: Over-temperature monitor synchronises firmware images"
status: Draft
priority: Low
owner: L. Samir
parent: INFO-Z4TW4B
order: 430
links:
  - type: verifies
    target: SYS-FMVZ4N
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
