---
id: TC-JVAAQY
type: test-case
title: "Verify: Heating controller notifys relay events"
status: Review
priority: Low
owner: L. Samir
parent: INFO-MS9DAG
order: 510
links:
  - type: verifies
    target: SYS-RAP7Z6
    confirmed: 8158ead818f6
  - type: verifies
    target: SW-GEQD7V
    confirmed: b4c2cec05ff8
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
