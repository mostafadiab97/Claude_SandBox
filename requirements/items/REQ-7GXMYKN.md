---
id: TC-W6DJTM
type: test-case
title: "Verify: Main PCB restores error conditions"
status: Review
priority: High
owner: S. Adel
tags:
  - release-2.0
parent: INFO-MACGC3
order: 1720
links:
  - type: verifies
    target: SYS-EKVD3G
    confirmed: da78120d2244
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
