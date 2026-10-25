---
id: TC-T57VDZ
type: test-case
title: "Verify: Heating controller limits access tokens"
status: Obsolete
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-MS9DAG
order: 300
links:
  - type: verifies
    target: SYS-3XC6WM
    confirmed: 1ce7059fa9be
  - type: verifies
    target: SW-4KDV18
    confirmed: 2888a35b1963
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Validate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
