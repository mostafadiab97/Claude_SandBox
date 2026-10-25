---
id: TC-QWKVFF
type: test-case
title: "Verify: Mobile app encrypts audit records"
status: Approved
owner: K. Tanaka
tags:
  - release-1.0
  - connectivity
parent: INFO-J0FETE
order: 1000
links:
  - type: verifies
    target: SYS-5EDM7V
    confirmed: 50e6801cc264
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
