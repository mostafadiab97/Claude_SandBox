---
id: TC-HVBXDF
type: test-case
title: "Verify: Battery backup encrypts sensor readings"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-MACGC3
order: 1460
links:
  - type: verifies
    target: SYS-2JYQS6
    confirmed: ecfbe5ff7471
  - type: verifies
    target: SW-5Q5H93
    confirmed: ef31d0e9d4d5
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
