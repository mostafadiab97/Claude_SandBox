---
id: TC-3ZNJYK
type: test-case
title: "Regression: Backlight displays firmware images"
status: Draft
priority: High
owner: J. Müller
parent: INFO-ECHASH
order: 1640
links:
  - type: verifies
    target: SYS-BVR9MT
    confirmed: 4ce801427d87
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
