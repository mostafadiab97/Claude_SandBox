---
id: TC-QBZ93F
type: test-case
title: "Verify: Touch display encrypts the operating mode"
status: Approved
priority: High
owner: M. Farouk
parent: INFO-HTSZ15
order: 770
links:
  - type: verifies
    target: SYS-EFJFCR
    confirmed: b46684aa0799
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Validate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
