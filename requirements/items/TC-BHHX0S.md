---
id: TC-BHHX0S
type: test-case
title: "Verify: OTA server logs schedule entries"
status: Approved
priority: High
owner: L. Samir
tags:
  - ux
  - cost
parent: INFO-7P4D8D
order: 120
links:
  - type: verifies
    target: SYS-0J3695
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
