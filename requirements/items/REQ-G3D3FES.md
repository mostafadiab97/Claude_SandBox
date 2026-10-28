---
id: REQ-G3D3FES
type: test-case
title: "Regression: Wi-Fi module synchronises humidity values"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-GDJV3Q
parent: REQ-6H15AV2
order: b23
links:
  - type: verifies
    target: REQ-DYXG5BT
    confirmed: 16a1100da795
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
