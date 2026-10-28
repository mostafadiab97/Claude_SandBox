---
id: REQ-J6SS86Z
type: test-case
title: "Verify: Zone valve notifys schedule entries"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - i18n
former-id: TC-5X7650
parent: REQ-XGWSK2K
order: aq
links:
  - type: verifies
    target: REQ-0YZEF7C
    confirmed: a4f989d37c98
  - type: verifies
    target: REQ-J2K9RV1
    confirmed: 02be29037617
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
