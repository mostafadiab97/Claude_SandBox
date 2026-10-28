---
id: REQ-WBR4MSW
type: test-case
title: "Verify: Cloud backend notifys safety limits"
status: Approved
priority: Medium
owner: L. Samir
former-id: TC-DS9K5M
parent: REQ-8351896
order: b0G
links:
  - type: verifies
    target: REQ-EBK9509
    confirmed: e3199b24d9a9
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
