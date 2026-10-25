---
id: TC-G5FNNW
type: test-case
title: "Verify: Pairing process calibrates sensor readings"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - power
  - cost
parent: INFO-F0M7VC
order: 660
links:
  - type: verifies
    target: SYS-2VEPK9
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
