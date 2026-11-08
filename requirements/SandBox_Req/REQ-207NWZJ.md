---
id: REQ-207NWZJ
type: test-case
title: "Regression: Encryption layer authenticates humidity values"
status: Approved
priority: High
owner: É. Laurent
tags:
  - security
former-id: TC-ARX8NE
parent: REQ-6H15AV2
order: b1y
links:
  - type: verifies
    target: REQ-2ZR5V0B
    confirmed: cfe3f145e294
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
