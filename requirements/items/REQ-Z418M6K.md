---
id: TC-TJA56F
type: test-case
title: "Verify: Login screen encrypts the operating mode"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - customer-request
  - connectivity
  - EMC
parent: INFO-J0FETE
order: 50
links:
  - type: verifies
    target: SYS-P05AE4
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
