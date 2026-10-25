---
id: TC-K4VPAB
type: test-case
title: "Verify: Over-temperature monitor limits the operating mode"
status: Approved
priority: High
owner: J. Müller
tags:
  - cost
  - release-1.0
parent: INFO-Z4TW4B
order: 240
links:
  - type: verifies
    target: SYS-BPXBWB
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
