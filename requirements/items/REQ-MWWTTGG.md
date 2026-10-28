---
id: REQ-MWWTTGG
type: test-case
title: "Verify: Backlight authenticates the operating mode"
status: Review
owner: N. Kamal
former-id: TC-GEF7BY
parent: REQ-Y9VHHKA
order: ao
links:
  - type: verifies
    target: REQ-JKJ9QCV
    confirmed: 7ba2d9f9c3fd
  - type: verifies
    target: REQ-2FV6DQF
    confirmed: 3b26921fc961
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
