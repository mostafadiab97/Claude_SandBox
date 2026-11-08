---
id: REQ-XXQKC8Z
type: test-case
title: "Verify: Watchdog logs the connection state"
status: Approved
owner: محمد علي
tags:
  - connectivity
  - i18n
former-id: TC-21Z9E9
parent: REQ-K6FGAY0
order: aw
links:
  - type: verifies
    target: REQ-W18RFR4
    confirmed: 2d379fb34255
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
