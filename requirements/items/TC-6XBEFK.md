---
id: TC-6XBEFK
type: test-case
title: "Verify: Local API detects firmware images"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - security
  - i18n
  - regulatory
parent: INFO-F0M7VC
order: 1120
links:
  - type: verifies
    target: SYS-E3TBDW
  - type: verifies
    target: SW-HKP9YP
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
