---
id: TC-BX7CG2
type: test-case
title: "Verify: OTA server switchs user preferences"
status: Draft
priority: Low
owner: J. Müller
tags:
  - ux
  - power
  - performance
parent: INFO-7P4D8D
order: 1450
links:
  - type: verifies
    target: SYS-P4DXM6
  - type: verifies
    target: SW-6T1MBB
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Limit error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
