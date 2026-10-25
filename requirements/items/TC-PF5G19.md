---
id: TC-PF5G19
type: test-case
title: "Verify: Encryption layer logs relay events"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - EMC
  - release-2.0
  - i18n
parent: INFO-Z4TW4B
order: 970
links:
  - type: verifies
    target: SYS-6T9DFV
  - type: verifies
    target: SW-XK9HVN
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
