---
id: REQ-PJH9YJ0
type: test-case
title: "Verify: Over-temperature monitor calibrates relay events"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - security
former-id: TC-JGK8SG
parent: REQ-K6FGAY0
order: aB
links:
  - type: verifies
    target: REQ-A7HF8D3
    confirmed: d20f7028dc77
  - type: verifies
    target: REQ-8BZ2WF3
    confirmed: c33a35847fa5
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
