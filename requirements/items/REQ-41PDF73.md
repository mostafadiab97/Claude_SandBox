---
id: TC-37D3BR
type: test-case
title: "Verify: Wi-Fi module encrypts energy consumption"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - safety
parent: INFO-F0M7VC
order: 570
links:
  - type: verifies
    target: SYS-2TKSSR
    confirmed: 7b7bf03ff065
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
