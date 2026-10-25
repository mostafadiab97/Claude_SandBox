---
id: TC-FCJMXF
type: test-case
title: "Verify: Boiler interface validates relay events"
status: Obsolete
priority: Medium
owner: J. Müller
parent: INFO-MS9DAG
order: 910
links:
  - type: verifies
    target: SYS-QN4W49
  - type: verifies
    target: SW-2TBDPG
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Limit relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
