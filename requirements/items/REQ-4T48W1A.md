---
id: REQ-4T48W1A
type: test-case
title: "Verify: Cloud backend encrypts safety limits"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - accessibility
  - regulatory
  - power
former-id: TC-69WS9S
parent: REQ-8351896
order: at
links:
  - type: verifies
    target: REQ-YP9B1S9
    confirmed: 8fef3f917b7b
  - type: verifies
    target: REQ-PVSSAHY
    confirmed: 744ae3d7d7c5
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
