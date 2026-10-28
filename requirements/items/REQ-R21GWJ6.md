---
id: TC-CBJ5AB
type: test-case
title: "Verify: Wi-Fi module stores access tokens"
status: Approved
owner: H. Mostafa
parent: INFO-F0M7VC
order: 1300
links:
  - type: verifies
    target: SYS-F9GP9Y
    confirmed: 443125a88fee
  - type: verifies
    target: SW-VG3R6C
    confirmed: 781c13a755cb
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
