---
id: REQ-JW085NB
type: test-case
title: "Verify: OTA server calibrates the set point"
status: Draft
priority: High
owner: Y. Saber
tags:
  - cost
  - customer-request
former-id: TC-JMS8X8
parent: REQ-8351896
order: aI
links:
  - type: verifies
    target: REQ-QKQMW5J
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
