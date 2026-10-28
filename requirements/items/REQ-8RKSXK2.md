---
id: REQ-8RKSXK2
type: test-case
title: "Verify: Boiler interface calibrates audit records"
status: Draft
priority: Low
owner: É. Laurent
tags:
  - i18n
  - accessibility
former-id: TC-1R5KVG
parent: REQ-XGWSK2K
order: b14
links:
  - type: verifies
    target: REQ-66AJY46
    confirmed: 0b9a1e94967b
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
