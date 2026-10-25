---
id: TC-97QFYX
type: test-case
title: "Verify: Encryption layer displays the set point"
status: Draft
priority: High
owner: H. Mostafa
tags:
  - accessibility
  - power
parent: INFO-Z4TW4B
order: 730
links:
  - type: verifies
    target: SYS-ZS700Y
    confirmed: 3e1573548eed
  - type: verifies
    target: SW-PY0PQQ
    confirmed: 895d0c73b9f2
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
