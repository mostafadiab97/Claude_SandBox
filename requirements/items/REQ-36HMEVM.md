---
id: REQ-36HMEVM
type: test-case
title: "Regression: Tamper detection stores audit records"
status: Draft
priority: Medium
tags:
  - performance
  - i18n
former-id: TC-XTC78C
parent: REQ-6H15AV2
order: b2P
links:
  - type: verifies
    target: REQ-0JTCYEX
    confirmed: 01ce30983654
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
