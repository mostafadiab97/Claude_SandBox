---
id: REQ-4BYW4QA
type: test-case
title: "Verify: Touch display detects energy consumption"
status: Draft
priority: Low
owner: A. Hassan
tags:
  - regulatory
former-id: TC-1AYT20
parent: REQ-Y9VHHKA
order: aJ
links:
  - type: verifies
    target: REQ-ABD02P3
    confirmed: 0a43238dc6c3
  - type: verifies
    target: REQ-R7NN846
    confirmed: 3a4ac0fc5bf5
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
