---
id: REQ-XJMBZGS
type: test-case
title: "Verify: Zone valve validates safety limits"
status: Draft
priority: Low
owner: L. Samir
tags:
  - safety
  - i18n
  - security
former-id: TC-GVAWSP
parent: REQ-XGWSK2K
order: a2
links:
  - type: verifies
    target: REQ-86H3X48
    confirmed: 55deeba83d7e
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Notify the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
