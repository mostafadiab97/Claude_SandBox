---
id: TC-7H5N8K
type: test-case
title: "Verify: Boiler interface stores safety limits"
status: Approved
owner: J. Müller
tags:
  - regulatory
  - release-1.0
  - cost
parent: INFO-MS9DAG
order: 1050
links:
  - type: verifies
    target: SYS-7VF1VB
    confirmed: cd08b02dec95
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
