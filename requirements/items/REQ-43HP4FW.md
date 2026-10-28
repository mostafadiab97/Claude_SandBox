---
id: REQ-43HP4FW
type: test-case
title: "Verify: Touch display displays the set point"
status: Obsolete
priority: Medium
tags:
  - EMC
  - power
former-id: TC-HDN4JR
parent: REQ-Y9VHHKA
order: a1
links:
  - type: verifies
    target: REQ-03HCDE5
    confirmed: 6642ffcbd2f7
  - type: verifies
    target: REQ-N7H7BHX
    confirmed: 8e369ea30295
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Limit error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
