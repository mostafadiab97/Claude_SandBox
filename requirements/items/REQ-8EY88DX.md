---
id: TC-S1W8QE
type: test-case
title: "Verify: Cloud backend detects the set point"
status: Approved
owner: A. Hassan
tags:
  - release-2.0
parent: INFO-7P4D8D
order: 970
links:
  - type: verifies
    target: SYS-C084T6
    confirmed: 60b474ed648f
  - type: verifies
    target: SW-XMBMSB
    confirmed: ab5edb451296
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
