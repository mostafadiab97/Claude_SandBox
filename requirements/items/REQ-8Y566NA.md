---
id: REQ-8Y566NA
type: test-case
title: "Verify: Schedule editor synchronises the set point"
status: Draft
priority: Medium
owner: J. Müller
former-id: TC-V4VMCY
parent: REQ-WR5ZJN9
order: aM
links:
  - type: verifies
    target: REQ-R8AR4B2
    confirmed: fe1a440a5bde
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
