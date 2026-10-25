---
id: TC-3PRAAJ
type: test-case
title: "Verify: Backlight authenticates the operating mode"
status: Obsolete
priority: High
owner: N. Kamal
parent: INFO-HTSZ15
order: 860
links:
  - type: verifies
    target: SYS-1SK52W
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Encrypt access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
