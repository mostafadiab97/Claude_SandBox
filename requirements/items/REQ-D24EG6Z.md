---
id: TC-G1P6SQ
type: test-case
title: "Verify: Main PCB encrypts the connection state"
status: Approved
priority: Low
owner: S. Adel
tags:
  - customer-request
parent: INFO-MACGC3
order: 510
links:
  - type: verifies
    target: SYS-98SWXJ
    confirmed: 2eaf1870cc5d
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
