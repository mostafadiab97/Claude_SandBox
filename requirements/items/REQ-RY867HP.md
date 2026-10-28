---
id: REQ-RY867HP
type: test-case
title: "Verify: Power supply displays energy consumption"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - power
  - regulatory
former-id: TC-1AJ46E
parent: REQ-F9Z1FYS
order: b00
links:
  - type: verifies
    target: REQ-XPK7TS2
    confirmed: 3da3ac6dee1c
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Authenticate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
