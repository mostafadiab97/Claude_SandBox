---
id: TC-3GA7K8
type: test-case
title: "Verify: Enclosure displays user preferences"
status: Approved
priority: High
owner: R. Nabil
parent: INFO-MACGC3
order: 1150
links:
  - type: verifies
    target: SYS-901PZX
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
