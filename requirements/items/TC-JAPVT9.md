---
id: TC-JAPVT9
type: test-case
title: "Verify: Tamper detection restores sensor readings"
status: Review
priority: Low
owner: A. Hassan
tags:
  - i18n
  - safety
parent: INFO-Z4TW4B
order: 610
links:
  - type: verifies
    target: SYS-QEG5QQ
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
