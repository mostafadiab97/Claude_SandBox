---
id: REQ-ZYZXE2S
type: test-case
title: "Verify: Zone valve reports the connection state"
status: Obsolete
priority: High
owner: A. Hassan
former-id: TC-FW3SHK
parent: REQ-XGWSK2K
order: a4
links:
  - type: verifies
    target: REQ-WT15HBZ
    confirmed: 839c3250cb67
  - type: verifies
    target: REQ-EC653CP
    confirmed: 073b39b4eae5
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
