---
id: REQ-YKTSFP3
type: test-case
title: "Verify: OTA server notifys the operating mode"
status: Draft
priority: Medium
owner: Y. Saber
former-id: TC-E1XCQ1
parent: REQ-8351896
order: aq
links:
  - type: verifies
    target: REQ-DKZ6T1N
    confirmed: dbe3e7f88972
  - type: verifies
    target: REQ-93PRYS5
    confirmed: d0a887012e16
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
