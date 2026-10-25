---
id: TC-YHGJWN
type: test-case
title: "Verify: Bluetooth LE link synchronises relay events"
status: Approved
priority: Low
owner: J. Müller
parent: INFO-F0M7VC
order: 1090
links:
  - type: verifies
    target: SYS-8HC07S
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
