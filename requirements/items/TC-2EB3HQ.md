---
id: TC-2EB3HQ
type: test-case
title: "Verify: Menu system stores sensor readings"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - i18n
  - connectivity
parent: INFO-HTSZ15
order: 1460
links:
  - type: verifies
    target: SYS-DVK0ST
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
