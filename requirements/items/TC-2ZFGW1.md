---
id: TC-2ZFGW1
type: test-case
title: "Verify: Bluetooth LE link stores firmware images"
status: Draft
owner: Y. Saber
tags:
  - connectivity
  - ux
parent: INFO-F0M7VC
order: 280
links:
  - type: verifies
    target: SYS-K61Y1H
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
