---
id: REQ-5YGN1PM
type: test-case
title: "Verify: Login screen stores relay events"
status: Draft
priority: High
owner: محمد علي
former-id: TC-7Z8CCF
parent: REQ-WR5ZJN9
order: b02
links:
  - type: verifies
    target: REQ-EK2Z568
    confirmed: fd79ba8f2af2
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
