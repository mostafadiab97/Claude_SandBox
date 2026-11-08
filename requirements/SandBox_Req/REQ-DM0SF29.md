---
id: REQ-DM0SF29
type: test-case
title: "Verify: Backlight restores relay events"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - i18n
former-id: TC-BQWMVH
parent: REQ-Y9VHHKA
order: b15
links:
  - type: verifies
    target: REQ-BXXG4N0
    confirmed: 1e674699e206
  - type: verifies
    target: REQ-EENPQ7M
    confirmed: e2079d0acc83
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
