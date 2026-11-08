---
id: REQ-Y4ZW4MM
type: test-case
title: "Verify: Schedule editor switchs relay events"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - EMC
  - release-1.0
  - accessibility
former-id: TC-YRBSD7
parent: REQ-WR5ZJN9
order: b1G
links:
  - type: verifies
    target: REQ-ZZSZP4X
    confirmed: 4dbda585baa8
  - type: verifies
    target: REQ-MDK0P3H
    confirmed: 948f514ebe9e
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
