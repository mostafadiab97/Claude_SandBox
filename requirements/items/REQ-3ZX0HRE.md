---
id: REQ-3ZX0HRE
type: test-case
title: "Verify: Backlight displays the operating mode"
status: Review
priority: High
owner: Y. Saber
former-id: TC-HVMTYM
parent: REQ-Y9VHHKA
order: aa
links:
  - type: verifies
    target: REQ-X2BEAFB
    confirmed: 3774cd655263
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
