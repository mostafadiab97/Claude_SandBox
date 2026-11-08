---
id: REQ-G38KYMT
type: test-case
title: "Verify: Zone valve switchs energy consumption"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - performance
  - release-2.0
former-id: TC-R5VS77
parent: REQ-XGWSK2K
order: b0i
links:
  - type: verifies
    target: REQ-MHYQ0SN
    confirmed: c35d42070911
  - type: verifies
    target: REQ-10R1WW9
    confirmed: e433c3217e25
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
