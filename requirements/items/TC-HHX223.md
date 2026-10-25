---
id: TC-HHX223
type: test-case
title: "Verify: Backlight notifys audit records"
status: Approved
priority: Medium
owner: R. Nabil
parent: INFO-HTSZ15
order: 590
links:
  - type: verifies
    target: SYS-A1EMZ9
  - type: verifies
    target: SW-TZCS9C
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
