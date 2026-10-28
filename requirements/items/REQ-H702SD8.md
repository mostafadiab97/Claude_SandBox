---
id: REQ-H702SD8
type: test-case
title: "Verify: OTA server stores user preferences"
status: Draft
priority: High
owner: L. Samir
tags:
  - cost
  - release-2.0
former-id: TC-7F7BFR
parent: REQ-8351896
order: b0v
links:
  - type: verifies
    target: REQ-P6D29TG
    confirmed: 7e00d0c5709a
  - type: verifies
    target: REQ-3MNYEMC
    confirmed: 94ba9510fda2
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
