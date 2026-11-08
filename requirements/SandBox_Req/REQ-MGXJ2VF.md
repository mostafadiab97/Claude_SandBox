---
id: REQ-MGXJ2VF
type: test-case
title: "Verify: Power supply detects error conditions"
status: Draft
priority: High
owner: N. Kamal
former-id: TC-A7YFWS
parent: REQ-F9Z1FYS
order: b0W
links:
  - type: verifies
    target: REQ-SHTW6AT
    confirmed: 1e8a0199df87
  - type: verifies
    target: REQ-WR6W86R
    confirmed: 37b64617ffc6
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
