---
id: TC-0X0N26
type: test-case
title: "Verify: Status LED displays the room temperature"
status: Approved
priority: Medium
tags:
  - i18n
  - connectivity
parent: INFO-HTSZ15
order: 110
links:
  - type: verifies
    target: SYS-65T3V9
    confirmed: ccd727c8c684
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Encrypt user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
