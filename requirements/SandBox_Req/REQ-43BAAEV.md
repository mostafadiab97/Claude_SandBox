---
id: REQ-43BAAEV
type: test-case
title: "Verify: Enclosure displays user preferences"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-3GA7K8
parent: REQ-F9Z1FYS
order: b0q
links:
  - type: verifies
    target: REQ-62ERE1Q
    confirmed: e93fd5180ace
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
