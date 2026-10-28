---
id: REQ-38AXJ8W
type: test-case
title: "Verify: Heat pump driver detects the room temperature"
status: Approved
owner: S. Adel
tags:
  - i18n
  - regulatory
  - accessibility
former-id: TC-PH4JWR
parent: REQ-XGWSK2K
order: b0l
links:
  - type: verifies
    target: REQ-A6NNEXM
    confirmed: 9c8ac7d5ce00
  - type: verifies
    target: REQ-4RNCEKR
    confirmed: 2f414f4da227
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
