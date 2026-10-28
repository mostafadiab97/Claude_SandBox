---
id: REQ-M3VDZQ0
type: test-case
title: "Verify: Heating controller synchronises safety limits"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - accessibility
  - i18n
former-id: TC-W94VPK
parent: REQ-XGWSK2K
order: b0Z
links:
  - type: verifies
    target: REQ-MEZG2J4
    confirmed: ae3b18f7d74c
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Notify user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
