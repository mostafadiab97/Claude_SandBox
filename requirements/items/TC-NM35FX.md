---
id: TC-NM35FX
type: test-case
title: "Verify: Regulation loop restores the set point"
status: Draft
priority: Medium
owner: H. Mostafa
parent: INFO-MS9DAG
order: 100
links:
  - type: verifies
    target: SYS-1WWXQV
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
