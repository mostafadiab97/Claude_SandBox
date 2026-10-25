---
id: TC-MENMWZ
type: test-case
title: "Verify: Over-temperature monitor measures the connection state"
status: Approved
owner: L. Samir
tags:
  - safety
parent: INFO-Z4TW4B
order: 1250
links:
  - type: verifies
    target: SYS-8FZWQN
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Restore sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
