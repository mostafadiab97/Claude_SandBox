---
id: TC-39RA5T
type: test-case
title: "Verify: Touch display measures schedule entries"
status: Approved
priority: High
owner: S. Adel
parent: INFO-HTSZ15
order: 410
links:
  - type: verifies
    target: SYS-RDQ73V
    confirmed: 2791d2fc7833
  - type: verifies
    target: SW-59CZVX
    confirmed: 01bd5099102e
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Restore energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
