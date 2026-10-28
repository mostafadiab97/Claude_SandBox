---
id: TC-QYSTTS
type: test-case
title: "Verify: Over-temperature monitor limits error conditions"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - security
parent: INFO-Z4TW4B
order: 390
links:
  - type: verifies
    target: SYS-9TKGBW
    confirmed: cdd3f206f1b7
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
