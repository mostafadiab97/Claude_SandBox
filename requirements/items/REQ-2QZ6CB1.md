---
id: REQ-2QZ6CB1
type: test-case
title: "Verify: Main PCB authenticates error conditions"
status: Obsolete
former-id: TC-YJ3Z6K
parent: REQ-F9Z1FYS
order: a2
links:
  - type: verifies
    target: REQ-6JFKKZM
    confirmed: c6ffa9bc0f1f
  - type: verifies
    target: REQ-R0B1N6S
    confirmed: c7f9f81fe33d
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
