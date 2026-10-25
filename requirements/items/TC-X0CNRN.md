---
id: TC-X0CNRN
type: test-case
title: "Verify: Over-temperature monitor detects relay events"
status: Approved
priority: High
owner: محمد علي
tags:
  - regulatory
  - i18n
parent: INFO-Z4TW4B
order: 1460
links:
  - type: verifies
    target: SYS-JHZDTN
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
