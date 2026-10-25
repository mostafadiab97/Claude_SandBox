---
id: TC-G691RX
type: test-case
title: "Verify: Battery backup stores audit records"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - release-2.0
parent: INFO-MACGC3
order: 200
links:
  - type: verifies
    target: SYS-1K9BKF
  - type: verifies
    target: SW-2GTPVQ
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
