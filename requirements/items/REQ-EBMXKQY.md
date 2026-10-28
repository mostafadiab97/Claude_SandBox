---
id: TC-3WRYSW
type: test-case
title: "Verify: Touch display displays access tokens"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-HTSZ15
order: 480
links:
  - type: verifies
    target: SYS-NADNAY
    confirmed: 7956526ae9f5
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
