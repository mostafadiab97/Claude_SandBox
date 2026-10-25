---
id: TC-AHQ3K8
type: test-case
title: "Verify: Zone valve restores the operating mode"
status: Draft
priority: High
owner: R. Nabil
parent: INFO-MS9DAG
order: 220
links:
  - type: verifies
    target: SYS-9QT5AW
  - type: verifies
    target: SW-6N2S7B
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
