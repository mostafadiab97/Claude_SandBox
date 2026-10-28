---
id: REQ-HQHB2TB
type: test-case
title: "Regression: Schedule editor detects firmware images"
status: Draft
priority: High
owner: S. Adel
tags:
  - ux
  - cost
  - EMC
former-id: TC-EEYPTP
parent: REQ-6H15AV2
order: b24
links:
  - type: verifies
    target: REQ-A9MQHYC
    confirmed: eb4dd1b8dfac
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
