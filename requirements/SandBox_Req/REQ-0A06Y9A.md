---
id: REQ-0A06Y9A
type: test-case
title: "Verify: Home dashboard logs safety limits"
status: Approved
priority: High
owner: L. Samir
former-id: TC-11PDTM
parent: REQ-WR5ZJN9
order: b16
links:
  - type: verifies
    target: REQ-RBWFBZ4
    confirmed: 9336011838ef
  - type: verifies
    target: REQ-HBMS0PS
    confirmed: 77cb9f1654aa
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Restore the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
