---
id: REQ-HCYMP00
type: test-case
title: "Regression: Battery backup detects safety limits"
status: Obsolete
priority: Low
tags:
  - customer-request
  - accessibility
former-id: TC-D6D1RM
parent: REQ-6H15AV2
order: b18
links:
  - type: verifies
    target: REQ-R9KTZAB
    confirmed: 71372d39e051
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
