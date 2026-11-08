---
id: REQ-XF0B7R7
type: test-case
title: "Verify: OTA server restores schedule entries"
status: Draft
priority: Low
owner: M. Farouk
former-id: TC-P0X89Q
parent: REQ-8351896
order: af
links:
  - type: verifies
    target: REQ-Z11QB4Y
    confirmed: e79eb16e0194
  - type: verifies
    target: REQ-KXXNJF0
    confirmed: d9cbe06956cd
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
