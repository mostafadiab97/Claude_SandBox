---
id: REQ-EXXEQGY
type: test-case
title: "Verify: Wi-Fi module switchs schedule entries"
status: Draft
priority: Medium
owner: J. Müller
former-id: TC-01K2AB
parent: REQ-67RQXCK
order: ah
links:
  - type: verifies
    target: REQ-1H9ZVHN
    confirmed: de7334e55ef0
  - type: verifies
    target: REQ-R8QX8XF
    confirmed: bbde3871e044
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
