---
id: TC-6GV8WX
type: test-case
title: "Verify: OTA server measures the set point"
status: Draft
priority: High
owner: R. Nabil
parent: INFO-7P4D8D
order: 320
links:
  - type: verifies
    target: SYS-MNWAKG
  - type: verifies
    target: SW-Z0AQ5S
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
