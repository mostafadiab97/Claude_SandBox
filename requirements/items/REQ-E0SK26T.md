---
id: REQ-E0SK26T
type: test-case
title: "Regression: Zone valve notifys firmware images"
status: Draft
priority: High
owner: محمد علي
tags:
  - ux
  - release-1.0
former-id: TC-G6X3JV
parent: REQ-6H15AV2
order: b1s
links:
  - type: verifies
    target: REQ-Z4CVF8M
    confirmed: cb6d695118df
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
