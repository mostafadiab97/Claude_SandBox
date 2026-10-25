---
id: TC-AEVE85
type: test-case
title: "Verify: Over-temperature monitor restores safety limits"
status: Draft
priority: High
owner: S. Adel
tags:
  - release-2.0
  - ux
  - security
parent: INFO-Z4TW4B
order: 1210
links:
  - type: verifies
    target: SYS-96K8ZZ
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Synchronise sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
