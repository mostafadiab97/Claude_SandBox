---
id: REQ-2MM1BS8
type: test-case
title: "Verify: Backlight stores schedule entries"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-M8A19V
parent: REQ-Y9VHHKA
order: a0
links:
  - type: verifies
    target: REQ-X5P461Y
    confirmed: c3ef2cb2745a
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
