---
id: TC-JMS8X8
type: test-case
title: "Verify: OTA server calibrates the set point"
status: Draft
priority: High
owner: Y. Saber
tags:
  - cost
  - customer-request
parent: INFO-7P4D8D
order: 190
links:
  - type: verifies
    target: SYS-2B7SGQ
    confirmed: 16e49588c382
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
