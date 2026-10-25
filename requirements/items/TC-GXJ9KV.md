---
id: TC-GXJ9KV
type: test-case
title: "Verify: Bluetooth LE link encrypts the operating mode"
status: Draft
priority: Low
owner: R. Nabil
parent: INFO-F0M7VC
order: 1400
links:
  - type: verifies
    target: SYS-RP2FET
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
