---
id: TC-WZ6XG2
type: test-case
title: "Verify: Pairing process measures safety limits"
status: Approved
priority: High
owner: É. Laurent
tags:
  - customer-request
  - accessibility
  - regulatory
parent: INFO-F0M7VC
order: 1240
links:
  - type: verifies
    target: SYS-NJ73ZK
    confirmed: cda235c01515
  - type: verifies
    target: SW-M4Q7EZ
    confirmed: 0f3b5272ad4b
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
