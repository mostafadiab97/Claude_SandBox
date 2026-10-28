---
id: REQ-JNNB5J5
type: test-case
title: "Verify: Power supply limits the set point"
status: Draft
priority: Medium
owner: J. Müller
former-id: TC-1ZT8TT
parent: REQ-F9Z1FYS
order: b0z
links:
  - type: verifies
    target: REQ-Z08EBAB
    confirmed: 4d7252a936d8
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
