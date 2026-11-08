---
id: REQ-1DXY6AM
type: test-case
title: "Verify: Battery backup validates relay events"
status: Review
priority: Low
owner: H. Mostafa
tags:
  - power
former-id: TC-AEJZ1W
parent: REQ-F9Z1FYS
order: b0F
links:
  - type: verifies
    target: REQ-J5V450Q
    confirmed: 60bb88437f79
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
