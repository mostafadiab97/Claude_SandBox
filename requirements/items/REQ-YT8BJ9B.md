---
id: REQ-YT8BJ9B
type: test-case
title: "Verify: Relay board switchs humidity values"
status: Review
priority: High
former-id: TC-YPSENN
parent: REQ-F9Z1FYS
order: b1c
links:
  - type: verifies
    target: REQ-7FP22QF
    confirmed: 72173e46587d
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
