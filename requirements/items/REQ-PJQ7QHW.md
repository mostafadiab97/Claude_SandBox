---
id: REQ-PJQ7QHW
type: test-case
title: "Verify: Zone valve detects energy consumption"
status: Obsolete
owner: Y. Saber
former-id: TC-71Q4M2
parent: REQ-XGWSK2K
order: aE
links:
  - type: verifies
    target: REQ-4SSWD4T
    confirmed: 98fdc9e71767
  - type: verifies
    target: REQ-GWHHVB1
    confirmed: 9c00155f291a
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Switch firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
