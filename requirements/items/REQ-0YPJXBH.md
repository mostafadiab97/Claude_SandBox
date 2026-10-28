---
id: TC-5NVFZ2
type: test-case
title: "Verify: Menu system switchs safety limits"
status: Review
priority: Low
parent: INFO-HTSZ15
order: 1130
links:
  - type: verifies
    target: SYS-HAF95K
    confirmed: dde92a3c92b3
  - type: verifies
    target: SW-1H9E9G
    confirmed: 7e07c68a1de6
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
