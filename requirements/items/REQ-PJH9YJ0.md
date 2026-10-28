---
id: TC-JGK8SG
type: test-case
title: "Verify: Over-temperature monitor calibrates relay events"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - security
parent: INFO-Z4TW4B
order: 120
links:
  - type: verifies
    target: SYS-7ECC65
    confirmed: d20f7028dc77
  - type: verifies
    target: SW-0CA54W
    confirmed: c33a35847fa5
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
