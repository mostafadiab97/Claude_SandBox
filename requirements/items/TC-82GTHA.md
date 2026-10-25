---
id: TC-82GTHA
type: test-case
title: "Verify: Bluetooth LE link encrypts audit records"
status: Obsolete
priority: Medium
owner: محمد علي
tags:
  - power
parent: INFO-F0M7VC
order: 1500
links:
  - type: verifies
    target: SYS-TGB5BV
    confirmed: efddaa3f87b9
  - type: verifies
    target: SW-W77SFQ
    confirmed: 8731c78398b2
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
