---
id: REQ-F39F8S1
type: test-case
title: "Verify: OTA server validates error conditions"
status: Draft
priority: Medium
former-id: TC-P3K385
parent: REQ-8351896
order: b0l
links:
  - type: verifies
    target: REQ-61CEQ7Y
    confirmed: e59e68c0f6b6
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
