---
id: REQ-1W8VCRD
type: test-case
title: "Verify: Backlight synchronises firmware images"
status: Draft
priority: Medium
owner: N. Kamal
former-id: TC-NJRFKR
parent: REQ-Y9VHHKA
order: b02
links:
  - type: verifies
    target: REQ-2QACV9V
    confirmed: 8656508483c4
  - type: verifies
    target: REQ-8G68JA8
    confirmed: b483650c28fc
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
