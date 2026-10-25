---
id: TC-D5A27K
type: test-case
title: "Verify: Regulation loop stores energy consumption"
status: Draft
priority: Low
owner: Y. Saber
parent: INFO-MS9DAG
order: 1030
links:
  - type: verifies
    target: SYS-2X1F3V
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
