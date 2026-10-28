---
id: REQ-RNV2K1Q
type: test-case
title: "Verify: Backlight reports humidity values"
status: Approved
priority: High
owner: J. Müller
tags:
  - power
former-id: TC-54B1Z4
parent: REQ-Y9VHHKA
order: b0p
links:
  - type: verifies
    target: REQ-JQ3RHFQ
    confirmed: 4e76eb2ccede
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
