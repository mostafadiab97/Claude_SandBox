---
id: TC-H43E1J
type: test-case
title: "Verify: Menu system authenticates humidity values"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - i18n
parent: INFO-HTSZ15
order: 1010
links:
  - type: verifies
    target: SYS-RJDTZ9
    confirmed: e76b1fb2127a
  - type: verifies
    target: SW-SZZCD2
    confirmed: 87a5a0a3990a
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
