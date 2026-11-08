---
id: REQ-XK8M0E4
type: test-case
title: "Verify: Backlight notifys the room temperature"
status: Approved
priority: Medium
owner: É. Laurent
former-id: TC-BHTN8X
parent: REQ-Y9VHHKA
order: b0H
links:
  - type: verifies
    target: REQ-YAYJM7A
    confirmed: 7b40fcf8dbb4
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
