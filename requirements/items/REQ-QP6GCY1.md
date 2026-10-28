---
id: TC-1A3TPW
type: test-case
title: "Verify: Enclosure displays sensor readings"
status: Approved
priority: High
owner: S. Adel
tags:
  - customer-request
  - power
  - release-1.0
parent: INFO-MACGC3
order: 1070
links:
  - type: verifies
    target: SYS-A6KWV7
    confirmed: 4488148b69d2
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
