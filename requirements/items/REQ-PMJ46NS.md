---
id: TC-8CW1G9
type: test-case
title: "Verify: Touch display reports user preferences"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-HTSZ15
order: 120
links:
  - type: verifies
    target: SYS-PRE7SJ
    confirmed: a718da154f60
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
