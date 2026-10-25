---
id: TC-QP7RE2
type: test-case
title: "Verify: OTA server switchs sensor readings"
status: Review
priority: Low
tags:
  - power
  - customer-request
parent: INFO-7P4D8D
order: 750
links:
  - type: verifies
    target: SYS-HSBZEM
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
