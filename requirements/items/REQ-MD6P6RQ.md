---
id: TC-7CFRGA
type: test-case
title: "Verify: Main PCB authenticates relay events"
status: Review
priority: High
owner: Y. Saber
tags:
  - regulatory
  - accessibility
  - security
parent: INFO-MACGC3
order: 1610
links:
  - type: verifies
    target: SYS-61H36K
    confirmed: c34ac0cd30f1
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
