---
id: TC-PBTRWG
type: test-case
title: "Verify: Over-temperature monitor restores sensor readings"
status: Review
priority: Low
owner: L. Samir
tags:
  - power
parent: INFO-Z4TW4B
order: 220
links:
  - type: verifies
    target: SYS-6B2AFX
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
