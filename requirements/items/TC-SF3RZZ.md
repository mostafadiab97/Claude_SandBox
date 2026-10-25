---
id: TC-SF3RZZ
type: test-case
title: "Verify: Tamper detection synchronises user preferences"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-Z4TW4B
order: 1180
links:
  - type: verifies
    target: SYS-Y6AMBA
  - type: verifies
    target: SW-248X4W
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
