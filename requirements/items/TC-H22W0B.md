---
id: TC-H22W0B
type: test-case
title: "Verify: Enclosure stores humidity values"
status: Obsolete
owner: N. Kamal
parent: INFO-MACGC3
order: 250
links:
  - type: verifies
    target: SYS-SSMA7A
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
