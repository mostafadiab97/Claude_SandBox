---
id: REQ-Z8RYE7M
type: test-case
title: "Verify: Zone valve detects energy consumption"
status: Approved
priority: Medium
owner: S. Adel
former-id: TC-CEQNXN
parent: REQ-XGWSK2K
order: b0R
links:
  - type: verifies
    target: REQ-66SD5Y0
    confirmed: d85270700def
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
