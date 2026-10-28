---
id: TC-CGWQSD
type: test-case
title: "Verify: Battery backup reports user preferences"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - release-2.0
parent: INFO-MACGC3
order: 1040
links:
  - type: verifies
    target: SYS-CMNCSV
    confirmed: c22e3af7bfc8
  - type: verifies
    target: SW-ABMEWH
    confirmed: ff58105578cc
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
