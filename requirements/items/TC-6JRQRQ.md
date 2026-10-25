---
id: TC-6JRQRQ
type: test-case
title: "Verify: Wi-Fi module reports humidity values"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - power
parent: INFO-F0M7VC
order: 930
links:
  - type: verifies
    target: SYS-4X1SRM
    confirmed: bc96873ba6c1
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
