---
id: REQ-QMQWJW3
type: test-case
title: "Verify: Battery backup notifys the operating mode"
status: Approved
priority: Low
former-id: TC-RFWPT8
parent: REQ-F9Z1FYS
order: b0S
links:
  - type: verifies
    target: REQ-EKP7AXG
    confirmed: 199fce62923b
  - type: verifies
    target: REQ-71R8P2G
    confirmed: 71eb8e44b2b0
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
