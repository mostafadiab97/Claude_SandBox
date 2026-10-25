---
id: TC-JA7HA0
type: test-case
title: "Verify: Boiler interface notifys user preferences"
status: Approved
owner: K. Tanaka
tags:
  - customer-request
  - accessibility
parent: INFO-MS9DAG
order: 1500
links:
  - type: verifies
    target: SYS-AZWQYS
    confirmed: 00d3546fe417
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Display user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
