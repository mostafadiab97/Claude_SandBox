---
id: TC-0HKJXN
type: test-case
title: "Verify: Main PCB measures user preferences"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - power
parent: INFO-MACGC3
order: 160
links:
  - type: verifies
    target: SYS-H9YARC
    confirmed: 65250d626484
  - type: verifies
    target: SW-MBM5E6
    confirmed: ee73796f28b9
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
