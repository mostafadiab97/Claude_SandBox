---
id: REQ-D2P13MK
type: test-case
title: "Verify: Login screen notifys firmware images"
status: Review
priority: Medium
owner: É. Laurent
former-id: TC-MXE337
parent: REQ-WR5ZJN9
order: b0L
links:
  - type: verifies
    target: REQ-1CGSZAR
    confirmed: 6bc9ba229103
  - type: verifies
    target: REQ-0Y3FPG4
    confirmed: 2381b283029d
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
