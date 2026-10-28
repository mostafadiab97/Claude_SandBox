---
id: REQ-FSMMBM5
type: test-case
title: "Verify: Mobile app detects safety limits"
status: Draft
priority: Medium
owner: Y. Saber
former-id: TC-GNTNTC
parent: REQ-WR5ZJN9
order: b0s
links:
  - type: verifies
    target: REQ-7V3TPE0
    confirmed: 463cc60a6f2f
  - type: verifies
    target: REQ-673CSJT
    confirmed: 3b6689097f0d
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
