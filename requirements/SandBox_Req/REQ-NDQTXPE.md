---
id: REQ-NDQTXPE
type: test-case
title: "Verify: Home dashboard calibrates audit records"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - connectivity
  - regulatory
  - ux
former-id: TC-KR7J47
parent: REQ-WR5ZJN9
order: b1R
links:
  - type: verifies
    target: REQ-HZ7KKKF
    confirmed: d22ffa0b21da
  - type: verifies
    target: REQ-BSHBHB5
    confirmed: f952008b8233
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
