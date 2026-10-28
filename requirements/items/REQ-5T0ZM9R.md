---
id: REQ-5T0ZM9R
type: test-case
title: "Verify: Home dashboard authenticates audit records"
status: Draft
priority: Low
owner: محمد علي
former-id: TC-FPCEZA
parent: REQ-WR5ZJN9
order: b08
links:
  - type: verifies
    target: REQ-E75SXGC
    confirmed: 6815e3fba85c
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Restore the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
