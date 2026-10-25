---
id: TC-DMEK82
type: test-case
title: "Verify: Zone valve notifys firmware images"
status: Approved
priority: Low
owner: J. Müller
tags:
  - regulatory
parent: INFO-MS9DAG
order: 1380
links:
  - type: verifies
    target: SYS-3RSNVX
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
