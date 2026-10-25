---
id: TC-6EYKE4
type: test-case
title: "Verify: Regulation loop switchs the room temperature"
status: Obsolete
priority: High
owner: K. Tanaka
parent: INFO-MS9DAG
order: 1370
links:
  - type: verifies
    target: SYS-FMTYXJ
  - type: verifies
    target: SW-TQ408P
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
