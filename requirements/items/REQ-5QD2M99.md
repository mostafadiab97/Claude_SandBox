---
id: REQ-5QD2M99
type: test-case
title: "Regression: Cloud backend stores safety limits"
status: Review
priority: High
owner: A. Hassan
tags:
  - safety
  - EMC
  - i18n
former-id: TC-1V5PA5
parent: REQ-6H15AV2
order: b0z
links:
  - type: verifies
    target: REQ-V6R6FNJ
    confirmed: c4f3af124d96
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
