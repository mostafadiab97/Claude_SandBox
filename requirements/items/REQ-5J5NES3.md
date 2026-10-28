---
id: TC-ZGWF4S
type: test-case
title: "Verify: Backlight reports the operating mode"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - accessibility
  - performance
  - ux
parent: INFO-HTSZ15
order: 630
links:
  - type: verifies
    target: SYS-E3DH60
    confirmed: 2a4bbbe46324
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
