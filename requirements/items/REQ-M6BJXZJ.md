---
id: REQ-M6BJXZJ
type: test-case
title: "Verify: Login screen limits energy consumption"
status: Review
priority: Medium
owner: N. Kamal
former-id: TC-DQMS8X
parent: REQ-WR5ZJN9
order: ad
links:
  - type: verifies
    target: REQ-444WTRT
    confirmed: aba31ae0874e
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
