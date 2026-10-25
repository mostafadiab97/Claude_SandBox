---
id: TC-13N9QX
type: test-case
title: "Verify: OTA server validates the room temperature"
status: Review
priority: Low
owner: Y. Saber
tags:
  - accessibility
  - EMC
parent: INFO-7P4D8D
order: 1020
links:
  - type: verifies
    target: SYS-RAASTZ
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
