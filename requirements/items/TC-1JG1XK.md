---
id: TC-1JG1XK
type: test-case
title: "Verify: Regulation loop displays sensor readings"
status: Draft
priority: High
owner: L. Samir
tags:
  - cost
  - safety
  - ux
parent: INFO-MS9DAG
order: 1550
links:
  - type: verifies
    target: SYS-SBQD9X
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Display firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
