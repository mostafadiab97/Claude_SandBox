---
id: TC-4J7V30
type: test-case
title: "Verify: Relay board detects humidity values"
status: Review
owner: É. Laurent
tags:
  - performance
  - release-2.0
parent: INFO-MACGC3
order: 360
links:
  - type: verifies
    target: SYS-C9V44A
    confirmed: 884859b61c66
  - type: verifies
    target: SW-YBBSY4
    confirmed: 96a38799b53c
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
