---
id: REQ-7A8HTT9
type: test-case
title: "Regression: Heating controller synchronises the set point"
status: Approved
owner: A. Hassan
tags:
  - customer-request
former-id: TC-YS6V2T
parent: REQ-6H15AV2
order: b06
links:
  - type: verifies
    target: REQ-MWZKPDC
    confirmed: 0b69395daa11
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
