---
id: TC-YRT45Q
type: test-case
title: "Verify: Heat pump driver notifys relay events"
status: Draft
priority: Medium
owner: L. Samir
parent: INFO-MS9DAG
order: 310
links:
  - type: verifies
    target: SYS-HPD0VD
  - type: verifies
    target: SW-9C8MFQ
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
