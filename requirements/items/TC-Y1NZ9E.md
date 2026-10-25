---
id: TC-Y1NZ9E
type: test-case
title: "Regression: Battery backup reports the operating mode"
status: Draft
priority: High
owner: L. Samir
tags:
  - release-2.0
  - cost
  - regulatory
parent: INFO-ECHASH
order: 1530
links:
  - type: verifies
    target: SYS-PT1QDH
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
