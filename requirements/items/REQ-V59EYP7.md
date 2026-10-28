---
id: REQ-V59EYP7
type: test-case
title: "Verify: Home dashboard switchs sensor readings"
status: Review
priority: Medium
owner: S. Adel
former-id: TC-93RRGP
parent: REQ-WR5ZJN9
order: b1C
links:
  - type: verifies
    target: REQ-KFEFVBF
    confirmed: d9f78fd2af42
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Measure the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
