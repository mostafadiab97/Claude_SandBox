---
id: TC-32BC90
type: test-case
title: "Verify: Device registry calibrates sensor readings"
status: Approved
priority: High
owner: A. Hassan
tags:
  - connectivity
  - release-2.0
parent: INFO-7P4D8D
order: 180
links:
  - type: verifies
    target: SYS-V0E8NK
    confirmed: 8b83909c9c36
  - type: verifies
    target: SW-S1E6DV
    confirmed: 780dea8581c6
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Switch relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
