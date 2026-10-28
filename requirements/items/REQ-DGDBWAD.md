---
id: REQ-DGDBWAD
type: test-case
title: "Verify: Backlight restores humidity values"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - release-2.0
former-id: TC-B1B2Z5
parent: REQ-Y9VHHKA
order: am
links:
  - type: verifies
    target: REQ-A10PCXF
    confirmed: 92ce5ba8e9a8
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
