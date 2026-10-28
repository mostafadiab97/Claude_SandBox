---
id: REQ-JDAHHG9
type: test-case
title: "Verify: Zone valve validates user preferences"
status: Review
priority: Medium
owner: M. Farouk
former-id: TC-1HK618
parent: REQ-XGWSK2K
order: ae
links:
  - type: verifies
    target: REQ-GSZGDN0
    confirmed: a44672610aca
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
