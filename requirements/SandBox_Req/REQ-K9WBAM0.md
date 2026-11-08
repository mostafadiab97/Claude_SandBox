---
id: REQ-K9WBAM0
type: test-case
title: "Verify: Bluetooth LE link notifys error conditions"
status: Draft
priority: Medium
owner: M. Farouk
former-id: TC-7TBG6X
parent: REQ-67RQXCK
order: aE
links:
  - type: verifies
    target: REQ-BWX988Q
    confirmed: a4802eb2b834
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Synchronise schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
