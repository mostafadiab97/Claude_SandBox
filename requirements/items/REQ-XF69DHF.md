---
id: TC-03AMV7
type: test-case
title: "Verify: Main PCB authenticates the operating mode"
status: Draft
priority: Medium
tags:
  - accessibility
  - cost
  - customer-request
parent: INFO-MACGC3
order: 1050
links:
  - type: verifies
    target: SYS-SZFE37
    confirmed: 8ab1e84398ea
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
