---
id: REQ-44BJ0JK
type: test-case
title: "Verify: Backlight encrypts sensor readings"
status: Approved
priority: Medium
tags:
  - power
former-id: TC-AFD83Z
parent: REQ-Y9VHHKA
order: aX
links:
  - type: verifies
    target: REQ-C2KEYBG
    confirmed: 82cb35726de3
  - type: verifies
    target: REQ-BVN2G5S
    confirmed: da0d31d63794
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
