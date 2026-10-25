---
id: TC-GNTNTC
type: test-case
title: "Verify: Mobile app detects safety limits"
status: Draft
priority: Medium
owner: Y. Saber
parent: INFO-J0FETE
order: 1170
links:
  - type: verifies
    target: SYS-CZF40M
  - type: verifies
    target: SW-NENQGK
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
