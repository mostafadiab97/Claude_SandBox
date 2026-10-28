---
id: TC-48J29E
type: test-case
title: "Verify: Encryption layer switchs schedule entries"
status: Review
priority: High
tags:
  - safety
  - performance
parent: INFO-Z4TW4B
order: 550
links:
  - type: verifies
    target: SYS-12Y20P
    confirmed: 83d1b44e122c
  - type: verifies
    target: SW-PNAXXQ
    confirmed: da50ffeb4c30
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
