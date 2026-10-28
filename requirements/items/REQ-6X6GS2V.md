---
id: REQ-6X6GS2V
type: test-case
title: "Verify: OTA server measures the set point"
status: Draft
priority: High
owner: R. Nabil
former-id: TC-6GV8WX
parent: REQ-8351896
order: aV
links:
  - type: verifies
    target: REQ-DGZD7G8
    confirmed: 979db4a6f2e3
  - type: verifies
    target: REQ-7WS1854
    confirmed: 1b912bd6dd9a
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
