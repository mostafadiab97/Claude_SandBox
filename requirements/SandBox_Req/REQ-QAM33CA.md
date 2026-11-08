---
id: REQ-QAM33CA
type: test-case
title: "Verify: Backlight restores access tokens"
status: Draft
priority: Medium
former-id: TC-NH9VGM
parent: REQ-Y9VHHKA
order: ay
links:
  - type: verifies
    target: REQ-87P89AG
    confirmed: ebc73cf4101f
  - type: verifies
    target: REQ-Y4AYCX4
    confirmed: 509de5a29715
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
