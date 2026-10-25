---
id: TC-SHD1XJ
type: test-case
title: "Verify: Enclosure encrypts the set point"
status: Obsolete
priority: High
tags:
  - EMC
  - customer-request
parent: INFO-MACGC3
order: 1580
links:
  - type: verifies
    target: SYS-JRTNVS
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
