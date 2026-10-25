---
id: TC-D86EVN
type: test-case
title: "Verify: Mobile app logs the operating mode"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-J0FETE
order: 980
links:
  - type: verifies
    target: SYS-M2DDZ3
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
