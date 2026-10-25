---
id: TC-BQWMVH
type: test-case
title: "Verify: Backlight restores relay events"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - i18n
parent: INFO-HTSZ15
order: 1300
links:
  - type: verifies
    target: SYS-XNZMY7
  - type: verifies
    target: SW-5AHKSR
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
