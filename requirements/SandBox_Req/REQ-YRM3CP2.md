---
id: REQ-YRM3CP2
type: test-case
title: "Verify: Relay board encrypts the set point"
status: Draft
priority: Medium
owner: محمد علي
former-id: TC-Y0JR5E
parent: REQ-F9Z1FYS
order: b17
links:
  - type: verifies
    target: REQ-TT6G6JA
    confirmed: 78aeb447b6ae
  - type: verifies
    target: REQ-MQK9CB8
    confirmed: 74dc91e27dbd
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Limit energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
