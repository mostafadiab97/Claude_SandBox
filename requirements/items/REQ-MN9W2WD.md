---
id: TC-0RGXV2
type: test-case
title: "Verify: Wi-Fi module authenticates error conditions"
status: Draft
priority: Medium
owner: A. Hassan
parent: INFO-F0M7VC
order: 910
links:
  - type: verifies
    target: SYS-5YJ231
    confirmed: 72fe6dc471a9
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Encrypt schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
