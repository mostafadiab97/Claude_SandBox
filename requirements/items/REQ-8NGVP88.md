---
id: TC-Q0E7GZ
type: test-case
title: "Verify: Wi-Fi module detects schedule entries"
status: Approved
priority: High
owner: J. Müller
tags:
  - regulatory
  - i18n
parent: INFO-F0M7VC
order: 800
links:
  - type: verifies
    target: SYS-AKZ1R4
    confirmed: da5ffbb2dc98
  - type: verifies
    target: SW-AT00E2
    confirmed: 7f592a075c3f
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
