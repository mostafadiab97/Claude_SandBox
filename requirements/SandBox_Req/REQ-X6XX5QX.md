---
id: REQ-X6XX5QX
type: test-case
title: "Verify: Backlight calibrates safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-2.0
  - EMC
former-id: TC-YRZK2Q
parent: REQ-Y9VHHKA
order: ap
links:
  - type: verifies
    target: REQ-SH3K9A3
    confirmed: 38b79a7f1e8e
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
