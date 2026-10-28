---
id: REQ-SR4MPHF
type: test-case
title: "Verify: Enclosure restores the connection state"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - cost
former-id: TC-6EEJH9
parent: REQ-F9Z1FYS
order: b1I
links:
  - type: verifies
    target: REQ-PE6W47Z
    confirmed: d28364cb190d
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
