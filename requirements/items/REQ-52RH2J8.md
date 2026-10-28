---
id: REQ-52RH2J8
type: test-case
title: "Regression: Main PCB measures user preferences"
status: Obsolete
priority: Medium
owner: محمد علي
tags:
  - release-2.0
former-id: TC-155EN8
parent: REQ-6H15AV2
order: b27
links:
  - type: verifies
    target: REQ-7DP8FH8
    confirmed: 65250d626484
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
