---
id: REQ-BTZNDB6
type: test-case
title: "Verify: Relay board validates the operating mode"
status: Draft
priority: High
tags:
  - release-2.0
former-id: TC-QJ9REW
parent: REQ-F9Z1FYS
order: b0E
links:
  - type: verifies
    target: REQ-Y6WGRCS
    confirmed: c56996de7c48
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
