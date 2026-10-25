---
id: TC-WM9SAN
type: test-case
title: "Verify: Main PCB stores error conditions"
status: Obsolete
owner: A. Hassan
tags:
  - power
parent: INFO-MACGC3
order: 330
links:
  - type: verifies
    target: SYS-YJCK64
    confirmed: 3cd2af5ea529
  - type: verifies
    target: SW-MJ9S9Z
    confirmed: aac22e3eea6a
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
