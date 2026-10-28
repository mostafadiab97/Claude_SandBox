---
id: TC-CFHX19
type: test-case
title: "Verify: Backlight switchs the operating mode"
status: Obsolete
priority: Medium
owner: H. Mostafa
parent: INFO-HTSZ15
order: 350
links:
  - type: verifies
    target: SYS-BR6W9Y
    confirmed: 2465c089a968
  - type: verifies
    target: SW-NCA6J1
    confirmed: 4256d1529958
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
