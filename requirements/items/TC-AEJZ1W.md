---
id: TC-AEJZ1W
type: test-case
title: "Verify: Battery backup validates relay events"
status: Review
priority: Low
owner: H. Mostafa
tags:
  - power
parent: INFO-MACGC3
order: 780
links:
  - type: verifies
    target: SYS-RW8T89
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
