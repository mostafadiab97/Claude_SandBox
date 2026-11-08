---
id: REQ-0FP5N4Z
type: test-case
title: "Verify: Backlight restores the operating mode"
status: Approved
owner: K. Tanaka
tags:
  - safety
  - ux
former-id: TC-E5RNVJ
parent: REQ-Y9VHHKA
order: a7
links:
  - type: verifies
    target: REQ-80WBXJW
    confirmed: c59e7f0fde76
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Restore humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
