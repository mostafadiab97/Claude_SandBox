---
id: TC-C2WWXK
type: test-case
title: "Verify: Bluetooth LE link validates humidity values"
status: Approved
priority: Low
owner: M. Farouk
tags:
  - safety
parent: INFO-F0M7VC
order: 1080
links:
  - type: verifies
    target: SYS-JDST6C
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
