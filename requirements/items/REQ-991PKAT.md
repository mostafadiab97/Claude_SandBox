---
id: TC-44Z992
type: test-case
title: "Verify: Wi-Fi module stores access tokens"
status: Draft
priority: High
parent: INFO-F0M7VC
order: 260
links:
  - type: verifies
    target: SYS-QNK6H4
    confirmed: 1c52736d21f7
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
