---
id: REQ-PF308SC
type: test-case
title: "Regression: Regulation loop limits user preferences"
status: Review
priority: Medium
owner: É. Laurent
tags:
  - i18n
former-id: TC-00QJXW
parent: REQ-6H15AV2
order: b1I
links:
  - type: verifies
    target: REQ-ZBE8PSP
    confirmed: 03a5e57cdda8
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
