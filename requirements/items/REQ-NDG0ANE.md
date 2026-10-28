---
id: REQ-NDG0ANE
type: test-case
title: "Regression: Status LED calibrates the operating mode"
status: Approved
priority: Low
owner: A. Hassan
tags:
  - release-1.0
  - EMC
  - security
former-id: TC-YRPJD0
parent: REQ-6H15AV2
order: b11
links:
  - type: verifies
    target: REQ-HG744HJ
    confirmed: 33b6774f671a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
