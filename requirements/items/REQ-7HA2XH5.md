---
id: REQ-7HA2XH5
type: test-case
title: "Verify: Enclosure validates humidity values"
status: Approved
priority: Low
owner: A. Hassan
former-id: TC-VGJJBJ
parent: REQ-F9Z1FYS
order: ai
links:
  - type: verifies
    target: REQ-CNQYTT2
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
