---
id: TC-KZZE4G
type: test-case
title: "Verify: Power supply restores humidity values"
status: Approved
priority: High
owner: S. Adel
tags:
  - accessibility
parent: INFO-MACGC3
order: 530
links:
  - type: verifies
    target: SYS-82CVHQ
    confirmed: 53eb98981ee7
  - type: verifies
    target: SW-ZQNECF
    confirmed: 616347694a14
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
