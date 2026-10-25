---
id: TC-SAA28C
type: test-case
title: "Verify: Backlight detects energy consumption"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-HTSZ15
order: 50
links:
  - type: verifies
    target: SYS-7C3GR4
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
