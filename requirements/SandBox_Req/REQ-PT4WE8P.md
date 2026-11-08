---
id: REQ-PT4WE8P
type: test-case
title: "Verify: Home dashboard synchronises schedule entries"
status: Review
priority: Low
owner: N. Kamal
former-id: TC-AD54Z2
parent: REQ-WR5ZJN9
order: b0Y
links:
  - type: verifies
    target: REQ-JYSBE1D
    confirmed: 6e1a778017fa
  - type: verifies
    target: REQ-WRES5AC
    confirmed: f76ca26e4df8
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
