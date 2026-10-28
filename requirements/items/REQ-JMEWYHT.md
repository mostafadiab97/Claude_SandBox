---
id: REQ-JMEWYHT
type: test-case
title: "Verify: Status LED restores audit records"
status: Approved
priority: Medium
tags:
  - power
former-id: TC-0V28A3
parent: REQ-Y9VHHKA
order: a9
links:
  - type: verifies
    target: REQ-DF485Z2
    confirmed: d0b47df35e0a
  - type: verifies
    target: REQ-6H34P9K
    confirmed: 17b26ef78c68
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
