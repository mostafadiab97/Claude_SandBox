---
id: TC-01BGNA
type: test-case
title: "Verify: Login screen validates relay events"
status: Review
tags:
  - accessibility
  - safety
  - performance
parent: INFO-J0FETE
order: 520
links:
  - type: verifies
    target: SYS-5N9QWY
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
