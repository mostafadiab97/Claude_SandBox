---
id: TC-7CVCPA
type: test-case
title: "Verify: Over-temperature monitor limits user preferences"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - ux
  - cost
parent: INFO-Z4TW4B
order: 1450
links:
  - type: verifies
    target: SYS-KFPJKE
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
