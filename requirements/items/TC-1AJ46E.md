---
id: TC-1AJ46E
type: test-case
title: "Verify: Power supply displays energy consumption"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - power
  - regulatory
parent: INFO-MACGC3
order: 630
links:
  - type: verifies
    target: SYS-M23G4X
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Authenticate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
