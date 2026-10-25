---
id: TC-PRHZF8
type: test-case
title: "Verify: Wi-Fi module stores the connection state"
status: Approved
priority: Low
owner: L. Samir
parent: INFO-F0M7VC
order: 270
links:
  - type: verifies
    target: SYS-KC9B1E
  - type: verifies
    target: SW-V9M4HQ
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
