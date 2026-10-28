---
id: TC-M8A19V
type: test-case
title: "Verify: Backlight stores schedule entries"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-HTSZ15
order: 10
links:
  - type: verifies
    target: SYS-Z7FHQ2
    confirmed: c3ef2cb2745a
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
