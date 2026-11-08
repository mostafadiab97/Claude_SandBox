---
id: REQ-QEXJJQG
type: test-case
title: "Verify: Over-temperature monitor stores the set point"
status: Draft
priority: High
owner: Y. Saber
tags:
  - regulatory
  - customer-request
  - ux
former-id: TC-EMHD52
parent: REQ-K6FGAY0
order: b0h
links:
  - type: verifies
    target: REQ-F2PF0EP
    confirmed: c65b58fe967d
  - type: verifies
    target: REQ-D9WZFHH
    confirmed: 91cf5b7270df
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
