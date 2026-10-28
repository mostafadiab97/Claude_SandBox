---
id: TC-N48DXP
type: test-case
title: "Verify: Main PCB displays access tokens"
status: Review
priority: Low
owner: K. Tanaka
tags:
  - i18n
parent: INFO-MACGC3
order: 940
links:
  - type: verifies
    target: SYS-VG4CAX
    confirmed: a7c55f8eb200
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
