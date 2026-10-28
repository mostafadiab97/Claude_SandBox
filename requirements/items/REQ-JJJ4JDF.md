---
id: REQ-JJJ4JDF
type: test-case
title: "Verify: Boiler interface logs user preferences"
status: Draft
priority: High
owner: N. Kamal
tags:
  - EMC
  - release-2.0
  - release-1.0
former-id: TC-7KGKSB
parent: REQ-XGWSK2K
order: b0P
links:
  - type: verifies
    target: REQ-DESXWYX
    confirmed: af53245ff967
  - type: verifies
    target: REQ-6HD66DQ
    confirmed: 320ede9579ea
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
