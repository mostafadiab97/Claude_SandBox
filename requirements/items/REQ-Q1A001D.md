---
id: REQ-Q1A001D
type: test-case
title: "Verify: Bluetooth LE link encrypts the operating mode"
status: Draft
priority: Low
owner: R. Nabil
former-id: TC-GXJ9KV
parent: REQ-67RQXCK
order: b1F
links:
  - type: verifies
    target: REQ-93NME1R
    confirmed: f29685558736
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
