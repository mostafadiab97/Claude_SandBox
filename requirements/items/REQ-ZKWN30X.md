---
id: REQ-ZKWN30X
type: test-case
title: "Verify: Relay board stores the set point"
status: Review
priority: Medium
owner: J. Müller
tags:
  - accessibility
former-id: TC-W1Y3EN
parent: REQ-F9Z1FYS
order: aK
links:
  - type: verifies
    target: REQ-1XFPJSJ
    confirmed: a7182b2229b0
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Calibrate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
