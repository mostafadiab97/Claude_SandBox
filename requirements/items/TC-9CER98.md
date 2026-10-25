---
id: TC-9CER98
type: test-case
title: "Verify: Battery backup encrypts audit records"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - EMC
parent: INFO-MACGC3
order: 1390
links:
  - type: verifies
    target: SYS-SHYKYB
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
