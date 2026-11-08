---
id: REQ-XXPJ5WJ
type: test-case
title: "Verify: Backlight stores safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - security
  - release-1.0
former-id: TC-0J8Q62
parent: REQ-Y9VHHKA
order: b0L
links:
  - type: verifies
    target: REQ-YQW5K1F
    confirmed: f3d27e3d9880
  - type: verifies
    target: REQ-B4X5FV4
    confirmed: 3908acfc255d
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
