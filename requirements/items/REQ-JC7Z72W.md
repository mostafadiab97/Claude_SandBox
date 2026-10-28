---
id: REQ-JC7Z72W
type: test-case
title: "Verify: Enclosure stores the room temperature"
status: Draft
priority: High
owner: É. Laurent
former-id: TC-1ZCRH6
parent: REQ-F9Z1FYS
order: b1Y
links:
  - type: verifies
    target: REQ-6JEC1MF
    confirmed: 3cfd57c0b514
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
