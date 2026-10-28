---
id: TC-M081Z4
type: test-case
title: "Verify: Pairing process switchs safety limits"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - EMC
parent: INFO-F0M7VC
order: 350
links:
  - type: verifies
    target: SYS-558WVB
    confirmed: 244554b45f3a
  - type: verifies
    target: SW-6PB6KG
    confirmed: 0a4b2ea82845
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Log user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
