---
id: REQ-4Y3E95Q
type: test-case
title: "Verify: Over-temperature monitor encrypts error conditions"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
former-id: TC-S7BZ5K
parent: REQ-K6FGAY0
order: b0H
links:
  - type: verifies
    target: REQ-Z3ES3B3
    confirmed: dfd0a878dd51
  - type: verifies
    target: REQ-RM9RV7Z
    confirmed: 44b6eb114f52
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Synchronise schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
