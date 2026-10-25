---
id: TC-Q1N6D1
type: test-case
title: "Verify: Battery backup restores sensor readings"
status: Draft
priority: High
owner: A. Hassan
parent: INFO-MACGC3
order: 300
links:
  - type: verifies
    target: SYS-C7RCJ1
    confirmed: 3bf493978048
  - type: verifies
    target: SW-SVBNV7
    confirmed: e80248c95f10
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
