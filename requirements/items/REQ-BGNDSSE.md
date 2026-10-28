---
id: TC-TKBCR6
type: test-case
title: "Verify: Relay board stores relay events"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - performance
  - i18n
  - EMC
parent: INFO-MACGC3
order: 1120
links:
  - type: verifies
    target: SYS-DKDQXS
    confirmed: 172d4f5ba54f
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
