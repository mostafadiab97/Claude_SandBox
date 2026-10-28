---
id: TC-8BJ0BB
type: test-case
title: "Verify: OTA server switchs schedule entries"
status: Review
priority: High
owner: محمد علي
parent: INFO-7P4D8D
order: 360
links:
  - type: verifies
    target: SYS-XQJCRE
    confirmed: edcb243104e3
  - type: verifies
    target: SW-3AAWDY
    confirmed: 7fe29834a8a6
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Report user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
