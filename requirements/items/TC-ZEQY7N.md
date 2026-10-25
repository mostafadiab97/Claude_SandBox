---
id: TC-ZEQY7N
type: test-case
title: "Verify: Enclosure limits sensor readings"
status: Approved
priority: Medium
owner: H. Mostafa
parent: INFO-MACGC3
order: 1370
links:
  - type: verifies
    target: SYS-48BXDV
    confirmed: b17b907e6406
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
