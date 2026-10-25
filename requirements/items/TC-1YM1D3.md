---
id: TC-1YM1D3
type: test-case
title: "Verify: Over-temperature monitor limits the set point"
status: Approved
owner: L. Samir
tags:
  - EMC
parent: INFO-Z4TW4B
order: 1370
links:
  - type: verifies
    target: SYS-9C32EE
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
