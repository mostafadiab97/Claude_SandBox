---
id: REQ-FR93BRE
type: test-case
title: "Verify: Heating controller measures the connection state"
status: Review
priority: Low
owner: S. Adel
tags:
  - security
  - i18n
former-id: TC-ZYAF7G
parent: REQ-XGWSK2K
order: b0B
links:
  - type: verifies
    target: REQ-SH0PS76
    confirmed: 77480e1be3cd
  - type: verifies
    target: REQ-9T091V1
    confirmed: 9d94b6822a15
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Log firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
