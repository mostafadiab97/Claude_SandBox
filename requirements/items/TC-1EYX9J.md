---
id: TC-1EYX9J
type: test-case
title: "Verify: Regulation loop detects energy consumption"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - regulatory
parent: INFO-MS9DAG
order: 1160
links:
  - type: verifies
    target: SYS-TXF8EG
    confirmed: 941441170ff9
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
