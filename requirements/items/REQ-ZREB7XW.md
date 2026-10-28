---
id: REQ-ZREB7XW
type: test-case
title: "Verify: Relay board limits the connection state"
status: Approved
priority: Medium
owner: A. Hassan
former-id: TC-A1682Q
parent: REQ-F9Z1FYS
order: b1f
links:
  - type: verifies
    target: REQ-VQB78TJ
    confirmed: 17c94a8ac671
  - type: verifies
    target: REQ-JCR5DBB
    confirmed: 836242716b54
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
