---
id: TC-Q19QMS
type: test-case
title: "Verify: Zone valve authenticates firmware images"
status: Draft
priority: Low
owner: R. Nabil
tags:
  - customer-request
  - accessibility
  - performance
parent: INFO-MS9DAG
order: 350
links:
  - type: verifies
    target: SYS-Y33EQ3
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
