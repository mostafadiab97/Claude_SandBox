---
id: TC-02FGWR
type: test-case
title: "Verify: Tamper detection notifys the set point"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - cost
  - connectivity
  - EMC
parent: INFO-Z4TW4B
order: 810
links:
  - type: verifies
    target: SYS-MR5CRK
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
