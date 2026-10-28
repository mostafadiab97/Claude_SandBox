---
id: TC-XTM095
type: test-case
title: "Verify: Wi-Fi module reports audit records"
status: Obsolete
owner: محمد علي
parent: INFO-F0M7VC
order: 920
links:
  - type: verifies
    target: SYS-TRKV8X
    confirmed: 598d6ef77c60
  - type: verifies
    target: SW-JRSXRR
    confirmed: 1355ccce7c2e
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
