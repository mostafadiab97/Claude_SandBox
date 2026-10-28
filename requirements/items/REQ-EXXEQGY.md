---
id: TC-01K2AB
type: test-case
title: "Verify: Wi-Fi module switchs schedule entries"
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-F0M7VC
order: 440
links:
  - type: verifies
    target: SYS-5NPG22
    confirmed: de7334e55ef0
  - type: verifies
    target: SW-9PFE3C
    confirmed: bbde3871e044
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
