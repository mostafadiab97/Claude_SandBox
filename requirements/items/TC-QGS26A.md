---
id: TC-QGS26A
type: test-case
title: "Verify: Local API limits audit records"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - connectivity
parent: INFO-F0M7VC
order: 160
links:
  - type: verifies
    target: SYS-N3WYBE
  - type: verifies
    target: SW-CKV9F9
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Validate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
