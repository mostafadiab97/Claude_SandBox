---
id: REQ-XTRPAYM
type: test-case
title: "Verify: Battery backup stores the room temperature"
status: Approved
priority: Medium
owner: N. Kamal
former-id: TC-803RWP
parent: REQ-F9Z1FYS
order: aP
links:
  - type: verifies
    target: REQ-PGMDNV9
    confirmed: e03e8a7a7686
  - type: verifies
    target: REQ-T440D0C
    confirmed: 3601ce92e4e2
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
