---
id: TC-FRZ10E
type: test-case
title: "Verify: Bluetooth LE link measures schedule entries"
status: Approved
owner: R. Nabil
tags:
  - customer-request
parent: INFO-F0M7VC
order: 310
links:
  - type: verifies
    target: SYS-CY6ETQ
    confirmed: fca3f3673c34
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
