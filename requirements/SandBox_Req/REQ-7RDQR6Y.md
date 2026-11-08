---
id: REQ-7RDQR6Y
type: test-case
title: "Verify: User account service calibrates humidity values"
status: Review
priority: Medium
owner: Y. Saber
tags:
  - connectivity
  - EMC
former-id: TC-P77JEY
parent: REQ-8351896
order: aa
links:
  - type: verifies
    target: REQ-8Q2DZX1
    confirmed: 639fddbac072
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
