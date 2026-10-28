---
id: REQ-5KPD7CN
type: test-case
title: "Verify: Backlight synchronises user preferences"
status: Review
priority: High
tags:
  - safety
  - regulatory
former-id: TC-SN4K3W
parent: REQ-Y9VHHKA
order: b0j
links:
  - type: verifies
    target: REQ-1X8RESD
    confirmed: efa36830708b
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Measure firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
