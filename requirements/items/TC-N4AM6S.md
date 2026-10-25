---
id: TC-N4AM6S
type: test-case
title: "Verify: Secure boot synchronises schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - EMC
  - regulatory
parent: INFO-Z4TW4B
order: 1510
links:
  - type: verifies
    target: SYS-J8A4BW
  - type: verifies
    target: SW-QZT0Y7
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
