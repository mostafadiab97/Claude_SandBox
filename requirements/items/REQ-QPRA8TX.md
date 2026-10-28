---
id: REQ-QPRA8TX
type: test-case
title: "Verify: Schedule editor measures energy consumption"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - regulatory
  - release-2.0
former-id: TC-2RVGJE
parent: REQ-WR5ZJN9
order: b0v
links:
  - type: verifies
    target: REQ-9B3KSET
    confirmed: cca1fb8df9ed
  - type: verifies
    target: REQ-W7RSXDH
    confirmed: 48092e93f8af
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
