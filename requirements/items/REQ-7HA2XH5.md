---
id: TC-VGJJBJ
type: test-case
title: "Verify: Enclosure validates humidity values"
status: Approved
priority: Low
owner: A. Hassan
parent: INFO-MACGC3
order: 450
links:
  - type: verifies
    target: SYS-QGGTRG
    confirmed: e1c94732a57d
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
