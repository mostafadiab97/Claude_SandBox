---
id: TC-HV7JWX
type: test-case
title: "Verify: Device registry synchronises energy consumption"
status: Approved
priority: Low
owner: A. Hassan
parent: INFO-7P4D8D
order: 870
links:
  - type: verifies
    target: SYS-QW4301
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
