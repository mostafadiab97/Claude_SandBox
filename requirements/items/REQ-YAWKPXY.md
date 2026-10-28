---
id: REQ-YAWKPXY
type: test-case
title: "Verify: Schedule editor measures safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - EMC
former-id: TC-DQQZFK
parent: REQ-WR5ZJN9
order: aa
links:
  - type: verifies
    target: REQ-DG88HFJ
    confirmed: 65eb9c0bc016
  - type: verifies
    target: REQ-12DBSQE
    confirmed: 83002d09327b
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
