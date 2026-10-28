---
id: TC-XJAF7S
type: test-case
title: "Verify: Enclosure synchronises energy consumption"
status: Approved
priority: Low
owner: M. Farouk
tags:
  - ux
  - customer-request
  - release-2.0
parent: INFO-MACGC3
order: 100
links:
  - type: verifies
    target: SYS-KT5254
    confirmed: 609b39c5ecd0
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Synchronise access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
