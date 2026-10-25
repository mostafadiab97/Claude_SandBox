---
id: TC-6EEJH9
type: test-case
title: "Verify: Enclosure restores the connection state"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - cost
parent: INFO-MACGC3
order: 1430
links:
  - type: verifies
    target: SYS-DAW84D
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
