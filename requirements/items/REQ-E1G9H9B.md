---
id: REQ-E1G9H9B
type: test-case
title: "Regression: Pairing process switchs safety limits"
status: Approved
priority: High
owner: A. Hassan
former-id: TC-JXFDK2
parent: REQ-6H15AV2
order: b0B
links:
  - type: verifies
    target: REQ-YSKSPN3
    confirmed: 244554b45f3a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
