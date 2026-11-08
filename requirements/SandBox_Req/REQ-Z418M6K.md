---
id: REQ-Z418M6K
type: test-case
title: "Verify: Login screen encrypts the operating mode"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - customer-request
  - connectivity
  - EMC
former-id: TC-TJA56F
parent: REQ-WR5ZJN9
order: a4
links:
  - type: verifies
    target: REQ-BCZ6972
    confirmed: 551fdad1c494
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Report user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
