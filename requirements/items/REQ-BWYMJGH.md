---
id: REQ-BWYMJGH
type: test-case
title: "Verify: Secure boot stores energy consumption"
status: Approved
priority: Low
owner: É. Laurent
tags:
  - i18n
  - EMC
former-id: TC-A4YXXT
parent: REQ-K6FGAY0
order: b0E
links:
  - type: verifies
    target: REQ-N8MVGME
    confirmed: 0f55b6e6a72b
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
