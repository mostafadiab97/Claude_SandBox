---
id: TC-2JBGRT
type: test-case
title: "Verify: Wi-Fi module synchronises sensor readings"
status: Approved
parent: INFO-F0M7VC
order: 550
links:
  - type: verifies
    target: SYS-0C2S4D
    confirmed: 306846e9f601
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
