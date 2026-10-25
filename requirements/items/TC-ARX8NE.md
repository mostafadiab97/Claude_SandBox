---
id: TC-ARX8NE
type: test-case
title: "Regression: Encryption layer authenticates humidity values"
status: Approved
priority: High
owner: É. Laurent
tags:
  - security
parent: INFO-ECHASH
order: 1850
links:
  - type: verifies
    target: SYS-5D666J
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
