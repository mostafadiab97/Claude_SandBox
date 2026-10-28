---
id: REQ-G8WZ1D6
type: test-case
title: "Verify: Zone valve encrypts safety limits"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
  - regulatory
  - EMC
former-id: TC-3BEN3P
parent: REQ-XGWSK2K
order: aM
links:
  - type: verifies
    target: REQ-S3K8TNJ
    confirmed: 4fcdac202dc1
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
