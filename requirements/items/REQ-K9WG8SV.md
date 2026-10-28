---
id: REQ-K9WG8SV
type: test-case
title: "Verify: Backlight displays energy consumption"
status: Obsolete
priority: High
owner: L. Samir
former-id: TC-DB5KZH
parent: REQ-Y9VHHKA
order: aZ
links:
  - type: verifies
    target: REQ-MZW0HWB
    confirmed: 004d18eb33a0
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
