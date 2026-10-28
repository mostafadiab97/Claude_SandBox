---
id: TC-7PY4X1
type: test-case
title: "Verify: Menu system encrypts audit records"
status: Review
priority: Low
tags:
  - performance
  - safety
parent: INFO-HTSZ15
order: 1090
links:
  - type: verifies
    target: SYS-26VKCE
    confirmed: 5c68d7d11bea
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
