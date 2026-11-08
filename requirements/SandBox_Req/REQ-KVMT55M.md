---
id: REQ-KVMT55M
type: test-case
title: "Verify: Over-temperature monitor detects schedule entries"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - regulatory
  - i18n
  - cost
former-id: TC-FKE04G
parent: REQ-K6FGAY0
order: b11
links:
  - type: verifies
    target: REQ-7Z26VSZ
    confirmed: 12318aa6eb13
  - type: verifies
    target: REQ-1VYDFK2
    confirmed: 8a35d4be4b3a
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Restore user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
