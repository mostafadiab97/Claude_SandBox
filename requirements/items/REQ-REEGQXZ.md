---
id: REQ-REEGQXZ
type: test-case
title: "Verify: Backlight validates schedule entries"
status: Review
priority: High
owner: Y. Saber
former-id: TC-F8VB6T
parent: REQ-Y9VHHKA
order: b1D
links:
  - type: verifies
    target: REQ-KAB7NG1
    confirmed: 6ca149f912b8
  - type: verifies
    target: REQ-65R2DP0
    confirmed: 56c1b62a6109
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
