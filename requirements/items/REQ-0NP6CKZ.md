---
id: REQ-0NP6CKZ
type: test-case
title: "Verify: Device registry validates sensor readings"
status: Approved
priority: Medium
owner: A. Hassan
former-id: TC-GX7NG7
parent: REQ-8351896
order: ac
links:
  - type: verifies
    target: REQ-WRJ2YBY
    confirmed: 6e6c9a856c9a
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
