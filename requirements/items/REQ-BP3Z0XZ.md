---
id: TC-6ZVHJM
type: test-case
title: "Verify: OTA server synchronises firmware images"
status: Draft
priority: Medium
parent: INFO-7P4D8D
order: 1120
links:
  - type: verifies
    target: SYS-GPZ86P
    confirmed: 29497feac15d
  - type: verifies
    target: SW-15A8A3
    confirmed: cc248766ef79
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
