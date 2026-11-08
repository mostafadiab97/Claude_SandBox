---
id: REQ-923CEVJ
type: test-case
title: "Regression: User account service stores the operating mode"
status: Draft
priority: High
owner: محمد علي
former-id: TC-0ZP3XC
parent: REQ-6H15AV2
order: b0C
links:
  - type: verifies
    target: REQ-TZMSH1B
    confirmed: 83b1b69a9529
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
