---
id: TC-M4J6MT
type: test-case
title: "Verify: Over-temperature monitor notifys firmware images"
status: Draft
tags:
  - customer-request
parent: INFO-Z4TW4B
order: 140
links:
  - type: verifies
    target: SYS-KJ0P5E
  - type: verifies
    target: SW-3W83V6
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Synchronise firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
