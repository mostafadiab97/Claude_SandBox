---
id: TC-KTVD07
type: test-case
title: "Verify: Encryption layer stores the operating mode"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - performance
parent: INFO-Z4TW4B
order: 720
links:
  - type: verifies
    target: SYS-7DMMJ1
    confirmed: 25d533559e9b
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
