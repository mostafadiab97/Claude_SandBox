---
id: REQ-GJHBHCZ
type: test-case
title: "Verify: Home dashboard limits energy consumption"
status: Review
priority: Medium
owner: M. Farouk
former-id: TC-8X1180
parent: REQ-WR5ZJN9
order: b1I
links:
  - type: verifies
    target: REQ-7P088ZG
    confirmed: 1f77718986ec
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
