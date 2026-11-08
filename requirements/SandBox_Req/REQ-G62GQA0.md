---
id: REQ-G62GQA0
type: test-case
title: "Regression: Enclosure displays the operating mode"
status: Draft
priority: High
owner: K. Tanaka
former-id: TC-BAXP7E
parent: REQ-6H15AV2
order: b0y
links:
  - type: verifies
    target: REQ-JQGMKTV
    confirmed: 11ed96679d8d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
