---
id: TC-Q38D71
type: test-case
title: "Verify: Main PCB validates the set point"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - customer-request
parent: INFO-MACGC3
order: 1010
links:
  - type: verifies
    target: SYS-EDRZBM
    confirmed: 248750d69b90
  - type: verifies
    target: SW-V18C92
    confirmed: 65a51bcffb34
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
