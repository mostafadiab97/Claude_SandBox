---
id: TC-XPQ955
type: test-case
title: "Verify: Local API detects the operating mode"
status: Approved
priority: High
owner: Y. Saber
tags:
  - cost
  - regulatory
  - ux
parent: INFO-F0M7VC
order: 1450
links:
  - type: verifies
    target: SYS-0MGEHH
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
