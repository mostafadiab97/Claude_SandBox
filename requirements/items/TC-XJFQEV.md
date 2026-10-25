---
id: TC-XJFQEV
type: test-case
title: "Verify: Wi-Fi module switchs audit records"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - release-2.0
parent: INFO-F0M7VC
order: 710
links:
  - type: verifies
    target: SYS-T6SZE0
  - type: verifies
    target: SW-9MRSNT
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
