---
id: TC-SNSQGX
type: test-case
title: "Verify: Touch display switchs access tokens"
status: Obsolete
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
  - connectivity
parent: INFO-HTSZ15
order: 1060
links:
  - type: verifies
    target: SYS-4A9C1C
    confirmed: 7e8a730cf0b5
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
