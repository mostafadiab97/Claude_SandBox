---
id: TC-9W50S5
type: test-case
title: "Verify: Encryption layer encrypts firmware images"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - power
  - cost
  - release-1.0
parent: INFO-Z4TW4B
order: 90
links:
  - type: verifies
    target: SYS-N4MBK3
    confirmed: 55991efb2c92
  - type: verifies
    target: SW-A12HZT
    confirmed: 1ce1d45dedc9
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
