---
id: TC-S78MNR
type: test-case
title: "Verify: Battery backup encrypts safety limits"
status: Draft
tags:
  - release-1.0
parent: INFO-MACGC3
order: 1110
links:
  - type: verifies
    target: SYS-CR4P8R
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
