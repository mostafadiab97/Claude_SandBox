---
id: TC-S7BZ5K
type: test-case
title: "Verify: Over-temperature monitor encrypts error conditions"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
parent: INFO-Z4TW4B
order: 800
links:
  - type: verifies
    target: SYS-Y8Q9XD
    confirmed: dfd0a878dd51
  - type: verifies
    target: SW-B45075
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
